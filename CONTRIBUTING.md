## Contribute to TID

:heart: First and foremost, thanks for your time and for taking the first steps to contribute. :heart:

 
<h2>Fork the Repo</h2>

First thing first, fork the repo so that you can make necessary changes to the file.

---

 
<h2>Add a Picture</h2>

Browse to the `images` folder and upload the wallpaper you want to share. Make sure to give it a proper name.

---

 
<h2>Add Picture Information</h2>

Open the `image_data.json` file. Inside the square brackets, insert the following snippet(**At the top**).

```json
{
  "image_name": ,
  "file_type": ,
  "orientation": ,

  "height": ,
  "width": ,

  "author": ,
  "author_link": ,

  "source": ,
  "source_link": ,

  "tags": []
},
  ```

|  Parameter  | Description                                                                                     |
|-------------|-------------------------------------------------------------------------------------------------|
| image_name  | Name of the image. Make sure that it matches the name that you used in the image folder         |
| file_type   | Type of the file. Can be anything. For example png, jpg, jpeg, etc.                             |
| orientation | Use either 0 or 1. Use 0 if the orientation is vertical. Use 1 if the orientation is horizontal. |
| height      | Optional. Can be absent. Delete the parameter if you don't give any value.                      |
| width       | Optional. Can be absent. Delete the parameter if you don't give any value.                      |
| source      | Mandatory. Source name of the image. Make sure you have the right to use it.                   |
| source_link | Mandatory. The actual download link of the image.                                               |
| author      | The author of the image. Can be the same as the source.                                             |
| author_link | Link to the author(Twitter, Instagram). Can be the same as the source_link.                         |
| tags        | Comma separated values inside the square brackets. Make sure to wrap with quotation(") marks. | 

  ---
 

 
<h2>Make a Pull Request</h2>

Once you are happy with the editing, head towards the [pull requests](https://github.com/Muhimen123/TID/pulls) tab. And make the PR. 
And hopefully it will get accepted with in a short amount of time. 

---
 

Thanks for contributing. Have a good day!!! :smile:

