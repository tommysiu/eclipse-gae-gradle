# eclipse-gae-gradle

A gradle project template for generating eclipse project with Google App Engine (GAE) nature.

## Usage

To generate the Eclipse project files, type `gradle cleanEclipse eclipse`


For detailed illustration of the gradle config, please refer to this [blog](http://tommysiu.blogspot.hk/2014/01/gradle-project-template-for-eclipse.html).


__Note__: to preserve the folder hierarchy, the file .gitignore has been put in several places. Remove them when you put real files into the project otherwise those files will be ignored by git.

## Directory Layout

    src/                --> src folder (all empty except .gitignore)
      main/             
        java/           
        resource/       
      test/             
        java/           
        resource/       
    war/                --> the web resources
      css/              
      js/               
      WEB-INF/
        classes/
        jsp/
        lib/
    build.gradle        --> the gradle configuration
