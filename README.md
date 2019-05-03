# imagereader
API for age and gender detection in images/videos/steams


HOW TO USE

`python manage.py runserver` => starts a local server on port 8000


Visiting
`http://localhost:8000/agegender/?urls=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSLEH-ehd6SQY4cPiU_64S401uFzipqYDXKLwyUDA9g3NXiztvAA`

Will give you the analysis on this image `https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSLEH-ehd6SQY4cPiU_64S401uFzipqYDXKLwyUDA9g3NXiztvAA`

`[u'Gender : Male, conf = 1.000', u'Age : (25-32), conf = 0.906']`


TODO:

Not robust enough for all urls
Not accurate enough
Age isn't granular enough
