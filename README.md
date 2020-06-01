# cicd-with-databricks-testing

databricks to/fro local to/fro remote
1. db to local --> either export files individually using source file format or export entire folder using databricks-cli; new versioned files can be copied/replaced to the same folder in local and git does the rest 
2. db from local --> using UI, import files from local to db; files don't get replaced in db automatically but new files are created with same names
3. local to remote --> git push origin <branch-name>
4. local from remote --> git pull
5. any merge processes can be done either on local or remote
