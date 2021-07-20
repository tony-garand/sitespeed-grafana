# Sitespeed.io

### Stepstorunsitespeed.io


- **Clone this repo**
- **Open docker and make sure docker is up and running**

- **`Run the following command`**]

Step1:
> docker compose up -d

staging 
> docker compose run --rm sitespeed.io --config config.json https://tnaaphptest.wpengine.com https://tnaaphptest.wpengine.com/continuing-education/ https://tnaaphptest.wpengine.com/our-approach/ https://tnaaphptest.wpengine.com/benefits/ https://tnaaphptest.wpengine.com/continuing-education/ https://tnaaphptest.wpengine.com/blog/ https://tnaaphptest.wpengine.com/about/ https://tnaaphptest.wpengine.com/your-team/

prod 
> docker compose run --rm sitespeed.io --config config.json https://tnaa.com https://tnaa.com/continuing-education/ https://tnaa.com/our-approach/ https://tnaa.com/benefits/ https://tnaa.com/continuing-education/ https://tnaa.com/blog/ https://tnaa.com/about/ https://tnaa.com/your-team/



# Grafana Dashboard

Step1: 
> Open http://127.0.0.1:3000/ for grafana dashboard


Step2:
> Click on `Home` link at the top left corner 

Step3: 
> Scroll down on the page 
Select the report as required  <br>
>>`Plus1` <br>
>>`Page Summary` <br>
>>`Site Summary`<br> 

