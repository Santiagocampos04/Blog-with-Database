#This is a Personal Project of a Blog. 

Using MongoDB Atlas, Express & Nodejs, EJS.

Online version: https://enigmatic-caverns-40037.herokuapp.com/

To Use this program should be create a File called:"config.json"
and there the password 
{"pass":xxxxxx}

In the App.js file:

you should choose your cluster and user
mongoose.connect("mongodb+srv://admin-xxxx:"+config.pass+"@clusterx-xxxx.mongodb.net/blogDB",
{
  useNewUrlParser: true,
  useUnifiedTopology: true
}
);

