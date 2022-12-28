---
layout: post
---


some content

When the form is submitted, it calls a function handleSubmit where it posts the data to a REST API.

We are using fetch to post the data to the a REST API. Here we are using the dummy REST API by httpbin.org and you can use the real API URL here.

Before passing the form data name, email and mobile number, we need to stringify it. JSON.stringify() function will take care of it.