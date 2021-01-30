Didn't see a lot of examples out there for this framework, so decided to create one.

## Step 1: Hello World of FastAPI, Stub out the API endpoints

- Display Hello World
- Map out endpoints we will need, comment what they will do

## Step 2: Mock the UI with Semantic UI and Jinja2 Templates

- Including CSS and JavaScript from the CDN

## Step 3: Database Design

- To design our database, we create SQLAlchemy models
- See what yfinance provides
- forwardPE, forwardEps, dividendYield, 50 Day, 200 Day, Close
- SQLAlchemy create_all
- Using SQL Lite for Demonstration purpose

## Step 4: Add a stock endpoint

- Background task to fetch info and add to db also
- Use any API tool to fetch the data
- Alternatively you can go to http://127.0.0.1:8000//docs or http://127.0.0.1:8000//redoc for fetch or post data

## Step 5: Wire home screen

- Show added stocks in a table

## Step 6: Filters to filter table

- Filter boxes on UI
- Use SQLALchemy to filter in db
- Use query parameters to filter

## Step 7: Modal to add stock tickers via UI

- You can add data by clicking on add stock button.

## Technologies Used

- FastAPI - For RESTAPI
- yfinance - For getting Stock Data
- sqlalchemy - For Database ORM
- jinja2 - For Template Engine
- uvicorn - For Server & auto reload
- aiofiles - For Static File Serving

## Wanna Test this App

- Clone the app from the git url.
- Go to Root Directory and run `pipenv shell`
- Then run `pipenv install`
- now run the Application with `uvicorn main:app --reload`
- Goto http://127.0.0.1:8000/ for view
- and http://127.0.0.1:8000//docs or http://127.0.0.1:8000//redoc for fetch or post data

# Create your issues is there is any
