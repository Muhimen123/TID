## Contribute to TID

First and foremost, thanks for your time and for taking the first steps to contribute.

<details>
  <summary>Fork the Repo</summary>

  First thing first, fork the repo so that you can make necessary changes to the file.

  ---
</details>

<details>
  <summary>Add a Picture</summary>

  Browse to the `images` folder and upload the wallpaper you want to share. Make sure to give it a proper name.

  ---
</details>

<details>
  <summary>Add Picture Information</summary>

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

  ---
</details>
