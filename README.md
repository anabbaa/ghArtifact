# ghArtifact

- is upload and download files generated by jobs
- add another step name it then uses action called upload-artifact with reserved key with then inden and name then enter in the same level type path and path is where to find the file which should be stored in it you can add folder or more or filed
- the main role of this upload to download an nother job sol add new step in another job name it uses actions/download-artifact with reserved word with name it with same name of the upload name

# output job

- is to have avalue on a job and reuse in another
- add another step to save a value in a job name it then run linuk command to find a file then excute command to output a name ten in the top level before define steps add outputs key inside it add variable from your choice then you can set our value in linkus echo command first before carly brackets type a output name from your choice it should not be as the name of the variable inside outputs and add = then target a file in github environment by adding >> \$GITHUB_OUTPUT this means we save this variable in github action with our valu the final step we will target in our variable in outputs a special context steps and then. then name of id special step so we will add id for this step then .outputs then .name of the outputs before the carly bracket in linuk command
