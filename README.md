# 📜 Post Translation Project with Google Translate API 🇬🇧➡️🇧🇷
> Transforming the world into a more connected place, one translation at a time! 🌍💬

This project uses the Google Translate API to translate 29,604 user posts from English to Portuguese in an automated way. Imagine being able to understand the content shared by people around the world, overcoming the language barrier! 💡

## 🎯 Objective
The main objective of this project is to translate user posts, originally written in English, into Portuguese, using the Google Translate API. This allows a vast amount of content to be accessed and understood quickly and efficiently, contributing to digital inclusion and the exchange of ideas between cultures. 🌐

## 🚀 Technologies Used
- Python 🐍: Main programming language for script development. - Google Translate API 🌍: Google's automatic translation service, which was used to translate the posts.
- Requests 📡: Python library for making HTTP requests, essential for interacting with the API.
- JSON 🧩: Format used to store and manipulate data from translated posts.
- Pandas 📊: For organizing and processing data in tabular format, facilitating analysis and export.

## 💡 How it Works
1. Collecting Posts: The project starts by collecting posts from users that are in English.
2. Sending to the API: For each post, the content is sent to the Google Translate API, where the translation is performed automatically.
3. Storing Data: After translation, the data is stored and organized with the help of Pandas.
4. Exporting: The result can be exported in different formats, such as XLSX, CSV or JSON, for later analysis or use in other applications.

## ⚙️ How to Run the Project
To run this project, just follow the steps below:

### 1. Clone the Repository
```bash
git clone https://github.com/antoniolmcandido/api-google-translate-datasets.git
```
### 2. Install Dependencies
Install all necessary dependencies using pip:
```bash
pip install pandas numpy tqdm googletrans
```
## 3. Run the Translation Script
With everything configured, just run the script to translate the posts. To do this, use Jupyter Notebook.

## 4. Get the Results
The script will generate a file posts_traduzidos.xlsx with the translated posts. You can open this file in Excel or another editor of your choice to view the results.

## 🎨 Example Output
Here's an example of what a translated post would look like:

| **Original Post** | **Translated Post** |
|----------------------------------------------|-----------------------------------------------|
| "I love exploring new places!" | "Eu adoro explorar novos lugares!" |
| "The weather today is just perfect." | "O clima hoje está Simplesmente Perfeito." |
| "Can't wait for the weekend to arrive!" | "Mal posso esperar para o fim de semana chegar!" |

## 🔧 How to Customize
You can customize the project to your needs! Some customization options:

- Change the translation language (e.g. from English to French, Spanish, etc.).
- Modify the way data is stored, exporting to other formats or integrating with databases.
- Configure the number of posts to be translated to suit your specific project.

## 📋 License
This project is licensed under the MIT license. See the LICENSE file for more details.

## 💬 Contributions
Contributions are welcome! If you have any improvements or fixes, feel free to open a pull request. Let's work together to improve accessibility and information exchange in the world! 🌍

## 💻 Quick Installation - Visual Step by Step
1. Clone the Repository.
2. Install the Dependencies.
3. Run the Script.

## 🙋‍♂️ Need Help?
If you have any questions or need help setting up the project, don't hesitate to open an issue in the repository. I'll get back to you as soon as possible! 😄

## 🎉 Acknowledgements
This project was inspired by the potential of modern APIs and the ease of accessing data from multiple sources. Thanks to the Google Cloud team for the amazing translation API, and to Python for its flexibility and power! 🙌

Let's transform communication in the world together! 🌍✨

## Googletrans Python Library Documentation
[https://pypi.org/project/googletrans](https://pypi.org/project/googletrans)
