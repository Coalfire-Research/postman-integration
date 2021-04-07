<p align="center">
  <img src="images/screen_image.png" alt="postman-integration"/>
</p>

# Postman Integration
Postman Integration is an extension to generate **Postman Collection fomat json file**.

This fork will check the requests for an X-Amz-Target header and automatically set the request name based on the AWS API method. It will also check if the request contains the string "arn:" and, if so, it will set the folder name to "Contains ARN". JAR file is in build/libs/postman-integration-1.2.jar

# Usage

* It's very easy. You can open Postman Integration window from context menu "Export as Postman Collection" on history tab. Multiple selection is OK!. Then  set up the followings on the window.

  * **Encoding** - This is encoding.
  
  * **Collection Name**: - Collection name which you want to name in Postman.

  * **Folder Name**: - Folder name which you want to name in Postman. You may use "Set ALL" button to set folder name to the field "Folder" for all of requests.

  * **Name**: - Request name which you want to name in Postman.

* Once you press **Export** button, this generate Postman Collection format json file. **You can import it into Postman**.

## License
MIT
