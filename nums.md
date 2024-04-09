1. First item
> Hello
2. Second item
3. Third item
4. Fourth item  

<br>

1. First item
   > Hello
1. Second item
1. Third item
1. Fourth item  

<br>

1. First item
8. Second item
3. Third item
5. Fourth item

<br>

1. First item

   ```Hello```

2. Second item
3. Third item
4. Fourth item

<br>
  


1. Create a `.vscode` folder (if not already present) in the root of your repository
2. Inside that folder, create a new file named `extensions.json` (if it doesn't already exist) with the following
   structure.

         ```
         {
         	"recommendations": ["sourcegraph.sourcegraph"]
         }
         ```

3. If the file does exist, append `"sourcegraph.sourcegraph"` to the `"recommendations"` array.
4. Push the changes to your repository for your other colleagues to share.
