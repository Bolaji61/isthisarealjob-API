<div align="center">

![hng](https://res.cloudinary.com/iambeejayayo/image/upload/v1554240066/brand-logo.png)

<br>

</div>

# isthisarealjob-API
 This is a project that can be used in verifying job invitations either as real or as fake. 
 
## How it Works
- The company sentiment analysis scrapes through nairaland comments and runs an analysis on what people are saying about the company.
- The address verifier makes use of google's Geocoding API in verifying address.
- The invitation text checker checks for grammatical errors in the invitation sent by the company.
- Then a confidence checker returns a result thats between `Fake` and `Real` on a scale of 0-10.

## Configuration 
- Install the packages in requirements.txt file using `pip -r install requirements.txt`
- Run the app using `python3 app.py`
- Open an API request Client such as Postman to make a post request using the json format in the API documentation `https://isthisarealjob-api.herokuapp.com/`
- Send a POST request to `http://127.0.0.1:5000` to receive a response
