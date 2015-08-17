sample_ubuntu1204_clojure
=========================

This sample helps you create a shippable.yml file for your clojure project on Shippable. Please refer to our [language specific documentation on clojure](http://docs.shippable.com/languages/#clojure) for more details.

### Build Image

The sample uses a clojure specific build image that's available for public use:
 [shippableimages/ubuntu1204_clojure](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_clojure)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_clojure/blob/master/Dockerfile)).

The lein version available in this image is lein2. You can use this image to run clojure builds.

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_clojure`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).

