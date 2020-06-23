# How to run this code?

## 1. Python script

Used for loading data from GTFS format zip file or link to it, merging and cleaning the data we need for drawing. In the end it is saved in a format we need for drawing in the frontend. 

### Steps: 

1. Open and run "load_data.py"
2. All stops from dataset are shown in terminal window
3. Choose two stops whose connections you want to see
4. Input them in the input fields in the terminal
5. You get feedback in the terminal in form of a table so you can see how the data looks, and the same table is saved localy
5.1. In case of zero connections between two stops, you will get error message "No available routes!"

## 2. Frontend




# Information-Visualisation - remove after use

https://github.com/electron/electron/blob/v10.0.0-beta.1/docs/tutorial/first-app.md

https://svgjs.com/docs/3.0/

http://igncp-demos.herokuapp.com/d3js/mareys-schedule

http://mbtaviz.github.io/trains-over-time/


**Setting up node_modules and electron:**

elevated CMD inside stringCharter file

npm install

npm rebuild

npm start

    (if error: npm install --save-dev electron)
   
npm install electron-packager -g

electron-packager .
