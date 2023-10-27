# Creating a static website using S3 on AWS
### • Cloud platform: AWS • Tools used: Text (Text editor), S3 (AWS) • Languages: Html

The following project is part of my `AWS` Solution Architect - Associate Certification.<br>
It can help you as a web entrepreneur, or web blogger, to deploy a static website very quickly using AWS.
<hr>
<b>Steps</b><br>
1. Create a bucket on S3 using a unique name <b>mys3247</b><be>

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/61966a54-e700-43c5-800a-b70cc4ff36e2)

2. Enable <b>Static Web Hosting</b> under the Properties Blade:

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/49915728-152a-40e6-bed7-f9e926b9885e)

3. Change permissions for your S3 so that <b>public access</b> is allowed by default public access is denied:

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/8ca7e9aa-2689-4378-ad31-0fbcbeab0a5d)


![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/615901f3-43e4-4d3f-827e-88589566f6e1)


4. Configure the <b>Bucket Policy</b> using this JSON File:

[Static Website on S3 - Bucket Policy](https://docs.google.com/document/d/1Y9Vjom6lbdKdfbw672FWGJ0WVO8gbemFUMsE72LqDac/edit)

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/87ea15d2-65a7-4e8a-8e7d-3fc4de1ecb49)

5. Upload your <b>index.html</b> file in your S3:

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/772dc866-6569-4a3d-8c48-c28fbb51b8a8)


<h2>Using Canva to create your index.html file</h2>

1. Go to [Canva.com](https://www.canva.com/)

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/6a194c94-1e5b-4f18-b1dd-700e8fb52735)

2. Search for the design you'd like to use for your static website

3. After making changes to your design, select <b>Share</b>:

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/ec94d4c6-ee03-48ed-87a8-6e2c162d5ba5)

4. Selcet <b>Embed</b>

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/051dc81c-925c-4065-beb8-4f8122c157a6)

5. Paste this into your Text Editor:

![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/65020d2f-0860-4fc3-80f6-5b63a0ae512a)


  > Click on Static Website Hosting to get the endpoint url.
  
There you go! Your website is online, you can visit it using the provided endpoint url.
  
![image](https://github.com/GraceAshu/Creating-a-static-website-in-using-S3-on-AWS/assets/75226472/301d8e90-7180-4c2a-9637-c41fc2627935)


[Visit my S3 static website](http://mys3247.s3-website-us-east-1.amazonaws.com)

## Author

* **Grace Ashu** - AWS Cloud series - Related tags: #S3 #Bucket #StaticWebsite
