# Introduction
This is a very simple SpringBoot application project highlighting how can we work out a Springboot web dependency project to AKS using ACR & Jib plugin.

# Steps
1. Downloaded the Springboot skelton from Spring initializer with web dependency, Java 8 & Maven
2. Imported in IDE (Eclipse) and made a simple Rest controller to return text on root request
3. Tested the project locally
4. Create an ACR using the Azure CLI and push image to ACR using Jib plugin 
5. Spin up AKS
6. Deploy ACR image to AKS
7. Create service to expose
8. Aha! We are done, verified !
