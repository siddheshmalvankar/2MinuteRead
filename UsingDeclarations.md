#Using Declaration

If at all you want to ensure your variable is dispose at the end of program scope. C# 8.0 provides a language feature using Declaration

```csharp
private static void ReadTextFile(string FilePath)
      {
          int counter = 0;
          string line;
          //using declartion here
          using System.IO.StreamReader file =   new System.IO.StreamReader(FilePath);
          while ((line = file.ReadLine()) != null)
          {
              Console.WriteLine(line);
              counter++;
          }

          file.Close();
          Console.WriteLine("There were {0} lines.", counter);         
         
          // file is disposed here
      }
      ```
      
In the preceding example, the file is disposed when the closing brace for the method is reached. 
That's the end of the scope in which file is declared.
