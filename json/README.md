THe users.json file is for reference. 
If you wish to fetch local data that you already have on your system in a json file, you can do so by fetching the users.json file.

I have used an API from "JSONPlaceholder" to fetch the json data on my site. 
The format to fetch any file in json is :-

*******
fetch('filename.json or any API link')
.then(response => response.json())
.then(json=>{
      console.log(json)
      })
*******


The data I have fetched is also displayed on the website, the local json file I created and the codes for both of them is provided in the json.html file and users.json file respectively.
