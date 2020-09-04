1

If you use VS CODE, you can use : Ctrl + Shift + P  -> Configure User Snippets -> PHP -> Enter

After that you can input code to file php.json :

"Show variable user want to see": {
  "prefix": "pre_",
  "body": [
     "echo '<pre>';",
     "print_r($variable);",
     "echo '</pre>';"
  ],
  "description": "Show variable user want to see"
}
After that you save file php.json, then you return to the first file with any extension .php and input pre_ -> Enter Done, I hope it helps.
