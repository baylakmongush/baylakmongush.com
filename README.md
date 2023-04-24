#baylakmongush.com

baylakmongush.com is my personal website, built with [the PortfolYOU Jekyll theme](https://github.com/YoussefRaafatNasry/portfolYOU), hosted on Kubernetes, and automated with Github Actions. This website serves as a platform for showcasing my projects and sharing my knowledge with the community.

Deployment
This website is deployed using Kubernetes and Helm Charts. Github Actions is configured to build and test the website on every push to the repository. If the tests pass, a Docker image is built and published to Github Package Registry. The Helm Charts are then used to deploy the new image to the Kubernetes cluster.
