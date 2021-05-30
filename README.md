This is a pilot project and develops a scoring solution for matrix-based math practices.
Backend: Python 3 + Flask
Frontend: JavaScript  (HTML + JavaScript for alpha version)
Fetch API is used to connect the frontend and backend.  
The key technical challenge is recognizing handwritten two-digit numbers written by young students, kindergarten - K6, in time pressure with CNN. This application also handles skewed and/or distorted images. 
This app uses Mongo DB to manage the uses, forms, scoring information. 
The Alpha version uses Flask-Login to manage the authentication with SQLalchemy and SQLite.
The app stores the uploaded images to app/static/img/upload/.
Under the upload folder, each user has its folder with the /user_name/date/uploaded_image_name/ such as /test_u/2020-10-04/Scan_test2/
The uploaded images are stored in the folder which name is a date. 
A folder which name is scanned image contains cell images and a reduced entire image (adjust.jpg).
MongoDB backup data taken with the mongodump is located under /app/dump. 
CNN training data and training app are not included in this folder.

