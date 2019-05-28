### Java Spring template project

This project is based on a GitLab [Project Template](https://docs.gitlab.com/ee/gitlab-basics/create-project.html).

Improvements can be proposed in the [original project](https://gitlab.com/gitlab-org/project-templates/spring).

### CI/CD with Auto DevOps

This template is compatible with [Auto DevOps](https://docs.gitlab.com/ee/topics/autodevops/).

If Auto DevOps is not already enabled for this project, you can [turn it on](https://docs.gitlab.com/ee/topics/autodevops/#enabling-auto-devops) in the project settings.

### 1 Run Locally

If you want to run the project locally create the docker image, run the following command inside the folder of the project

`docker build . --tag <name_of_image:version_of_image>`

then run the container of that image

`docker run -P <name_of_image:version_of_image>`

the -P option is used to map the port inside docker (the expose in the dockerfile) to the host.

### 2 Update changes to gitlab