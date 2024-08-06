
# How to use Cloudflare Tunnels for hosting from your Local Machine/Homelab
What is a  Cloudflare Tunnels

Cloudflare Tunnels is a service that provides a secure way to connect your internal resources (like web servers, databases, or other applications) to the internet without exposing them directly to the public.

Note:- to get access of Cloudflare Tunnels (Zero Trust) you have add a credit card in you Cloudflare account once you added the card successfully you see somethink like this 

![home page for tunnles ](https://github.com/user-attachments/assets/8da6c29c-6323-4f3c-b3bb-b1c9870afe04)

Then select Tunnels option in network section (as shown)

![select tunnel option ](https://github.com/user-attachments/assets/5327af4d-c70f-4384-989e-b78914fe3822)

Then you see something like this now you have to select ADD A TUNNEL option (as shown)

![add tunnel](https://github.com/user-attachments/assets/41b2589b-eb3d-4b75-b711-98b717aa84c1)

Once you clicked on ADD A TUNNEL you see some page like this now you have select a tunnel type we will go with defualt as recommended so just select and click NEXT  

![click next](https://github.com/user-attachments/assets/2764713f-1691-4595-85c6-2537168f78ec)

Once you click next you see a page like this here you have to NAME YOU TUNNEL you can use any name and just click SAVE TUNNEL 

![give a name to your runnel ](https://github.com/user-attachments/assets/2769459d-3e8a-4eb7-8340-e676a33202ea)

After adding tunnel name and savinf the tunnel you see a page like this 

Now you have to select the operating system and the architecture type of your local machine (in which you hosting your application) it can be a Windows,Mac,Linux or even you can use Docker i will be going with Debian becoz am using a ubuntu locak machine for hosting 

Once you selected your OS and Architecture cloudflare will provide you the code you have to run in the local machine (as shown) just copy and paste in the terminal of your local machine

![select the os you in and copy the command ](https://github.com/user-attachments/assets/2a6d847c-47a4-4aae-8ee0-8780ca32b3af)

Copy the commmand and Paste it in your local machine terminal (as shown)

![copy the commadn and hi ](https://github.com/user-attachments/assets/56201899-0d66-4bef-81e3-83cf0f684949)

Once you run the code it should say LINUX SERVICE FOR CLOUDFLARED INSTALLED SUCCESSFULLY  if your terminal throw any error repeart above steps carefully 

![it should say succesfull](https://github.com/user-attachments/assets/0db4eb84-69e6-4ce1-857b-ecb78a8a8d9c)

After running command successfully you see a Connector STATUS CONNECTED and click next 

![WhatsApp Image 2024-08-06 at 22 33 46_c4a837cf](https://github.com/user-attachments/assets/6e2dde2a-2cfd-4e7e-9cb3-86f67ec31c40)

Once the Connection is connected you see a page someting like this here you hsve to add your domain Also you can add a custom sub domain (in red box )

And also have to tell cloudflare where the service is running on local machine by giving it the type of service (HTTP,HTTPS) running and URL of the running service for me its HTTP and loclhost becoz am running the service in nginx if you using something else for running the service you have to put that use like localhost:3000 once all thta done click next 

NOTE:- For cloudflare tunnels you have to have a domin which is on your cloudflare account you can not add a domain from other provider (you can transfer a domain to cloudflare to use that in tunnels) 

![add your domain and local host ](https://github.com/user-attachments/assets/5e900513-0755-432f-8d9f-136a739f6425)

Once all configration done you see your tunnel is created 

![done](https://github.com/user-attachments/assets/86c797d0-d1bf-4939-9d36-13e33e895cec)

Now you can visit the domain to see your local hosted service is hosted on the internet with your custome domain 

![hosted on domin ](https://github.com/user-attachments/assets/c558a121-7eb1-4459-8d9c-e3ea54bcb572)


THIS IS HOW YOU CAN EXPOSE YOUR LOCAL MACHINE TO THE INTERNET 



