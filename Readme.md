# [Bus E-card](https://darshan1005.github.io/Bus-e-Card/)
## [Files](https://drive.google.com/drive/folders/1sLzo61SzvgpPWOVidBgF1KhJz0eOI2Pt?usp=sharing)
Click title for DEMO only mobile version avaliable. Watch on inspect
## User Flow 
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/cdd8b4c9-08e9-4a21-831b-91183d9d4761)
## IOT flow
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/dbd97f71-f5d7-4be8-a036-56c0c4ba8de4)

### Mobile Version Only
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/ee01e2de-2398-4b2c-8dab-7d72054fc3f3)
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/051b1379-69eb-47da-84d0-0cd059b4d029)
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/99695f14-7216-4af7-9a7a-83e56ea9d729)
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/00b2e38b-ee4f-42a8-b219-623f9bf939fb)
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/4659f521-c413-4ee3-98a2-0672d803207c)
![image](https://github.com/darshan1005/Bus-e-Card/assets/114302987/63c68ffc-a9c7-4f0e-be61-f2d9b7683249)

-----------------------------

```FolderStructure
    chatbot_project/
    ├── public/
    │   ├── index.html
    │   ├── styles.css
    │   └── script.js
    ├── server/
    │   ├── app.js
    │   ├── scrape.js
    │   └── clean.js
    ├── data/
    │   ├── scraped_data.json
    │   └── cleaned_data.json
    ├── package.json
    └── README.md
```
### create a project
#### npm init
### Install Packages
#### npm install axios fs body-parser express cheerio

1. check Json which must be close to this
```Package.json
{
  "name": "chatbot_project",
  "version": "1.0.0",
  "main": "server/app.js",
  "scripts": {
    "start": "node server/app.js"
  },
  "dependencies": {
    "axios": "^0.21.1",
    "body-parser": "^1.19.0",
    "cheerio": "^1.0.0-rc.3",
    "express": "^4.17.1"
  }
}
```
2. Run the Scraping and Cleaning Scripts:
- Run node server/scrape.js to scrape the data and save it to scraped_data.json.
- Run node server/clean.js to clean the data and save it to cleaned_data.json.
3. Start the Server:
- Run npm start to start the Express server.
4. Open the UI:
- Open your browser and navigate to http://localhost:3000 to interact with your chatbot.

```Conclusion
This setup provides a basic chatbot UI similar to WhatsApp, handling user input and displaying bot responses. Adjust the YOUR_API_KEY and your_endpoint placeholders with your actual Gemini API details.
```
