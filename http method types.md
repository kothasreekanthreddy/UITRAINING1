What are different types of HTTP Methods

1) GET Method - This method is used fetch data using some params - fetching 100 users
2) Post Method - IF you want to add new user or update user we will be using Post menthod - creating user or udate user
3) Put Method  - We will be using for udate purpose only and not creating - updating user
4) Delete Method - This method will be used to delete information - deleting user



For Get Method:

Sample url for get request type:

GET Request URL:

URL : Http://your-own-website.com/products?productmodel:mi
type: GET

Back end people will collect this request url and they can identify firstname and lastname of the query parameters and can the data from database and will send response to User

Response always will be in the JSON format or json

data:{
    "firstname":"Sreekanth",
    "lastname":"kotha",
    "id":"1",
    "employer":"sony"
}


Post Request Type :

we will have a form to create new user or udate user and will fill the data and submit

URL: Http://your-own-website.com/products
type: Post
data: {
    "firstname":"Divya",
    "lastname":"punamalli",
    "id":"2",
    "employer":"tcs"
}

Response :

Yes the data has been saved and will also send back the saved object 

data: {
    "firstname":"Divya",
    "lastname":"punamalli",
    "id":"2",
    "employer":"tcs"
}


Put Request Type :

we will have a form update user and will fill the data and submit

URL: Http://your-own-website.com/users
type: Post
data: {
    "firstname":"Divyashree",
    "lastname":"punamalli",
    "id":"2",
    "employer":"tcs"
}

Response :

Yes the data has been saved and will also send back the saved object 

data: {
    "firstname":"Divyashree",
    "lastname":"punamalli",
    "id":"2",
    "employer":"tcs"
}

Delete Request Type:

URL: Http://your-own-website.com/users/deleteapi/id=2
type: Delete
