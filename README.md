# Docker-lab3
#Create your bridge network, two containers from ubuntu image with different 
names and try to ping each other using NAME. (using cli)
- creating my network called my-bridge with 2 containers ubuntu1 and ubuntu2 
![Screenshot (836)](https://user-images.githubusercontent.com/93229250/229402503-33630df5-b654-47c3-84e0-7f4e28f7a4fc.png)
- in each container we install the package to get "ping" command 
![Screenshot (837)](https://user-images.githubusercontent.com/93229250/229402853-2162a8bc-6fa1-455c-b0be-110091be52fc.png)
- then ping to each from the other 
![Screenshot (838)](https://user-images.githubusercontent.com/93229250/229402907-b373c92c-b2f7-4ac7-b5ae-0709bc84179f.png)
![Screenshot (839)](https://user-images.githubusercontent.com/93229250/229402916-4acf8054-ecc8-4b1a-aefc-fc79afba0678.png)

--------------------------------------------------------------------------------------------------------------------------

#Create your bridge network, two containers from ubuntu image with different 
names and try to ping each other using NAME. (using compose file)
- creating file named docker-compose.yml contains 2 services of ubuntu1 and ubuntu2 and my network (my-bridge) 
![Screenshot (840)](https://user-images.githubusercontent.com/93229250/229403317-6ed02345-44e3-4856-ad63-69b2b665b742.png)
- activate 2 containers and install the package to get "ping" command and create my network 
![Screenshot (847)](https://user-images.githubusercontent.com/93229250/229403509-f41668b8-3974-4c6c-b1cd-d863c76bf4d0.png)
![Screenshot (843)](https://user-images.githubusercontent.com/93229250/229403817-df4efa0c-e9f8-4c57-a778-279da0ef1953.png)
- then ping to each from the other 
![Screenshot (842)](https://user-images.githubusercontent.com/93229250/229403890-860d205d-4353-49c7-8f20-98b2cdd4c77b.png)
![Screenshot (845)](https://user-images.githubusercontent.com/93229250/229403902-5969525c-daf3-4289-8cb7-bfe3121d67f6.png)


