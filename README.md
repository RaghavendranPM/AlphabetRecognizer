# Alphabet Recognizer

#### Simple Optical Character Recognizer 

[This Image processing program](http://minhaskamal.github.io/AlphabetRecognizer) can convert image of English writing (like- [this](https://user-images.githubusercontent.com/5456665/27283353-a5e44fdc-5515-11e7-9dbb-ee4e966c7cfe.png)) to text. It simply uses **Template Matching** strategy for character recognition.

### How to Run?
1. [Download Alphabet Recognizer](https://github.com/MinhasKamal/AlphabetRecognizer/archive/master.zip), and [import](http://www.codejava.net/ides/eclipse/import-existing-projects-into-eclipse-workspace) it in your IDE.
2. [Download egami.jar](https://github.com/MinhasKamal/Egami/blob/release/Egami-V0.1.jar?raw=true) from [project- Egami](https://github.com/MinhasKamal/Egami), and [integrate](https://stackoverflow.com/a/3280451/4684058) it in the project's build path.
3. For training the machine run **[Train.java](https://github.com/MinhasKamal/AlphabetRecognizer/blob/master/src/com/minhaskamal/alphabetRecognizer/Train.java)**.
4. For testing run **[Predict.java](https://github.com/MinhasKamal/AlphabetRecognizer/blob/master/src/com/minhaskamal/alphabetRecognizer/Predict.java)** (change file-paths in the *main* method according to your need).

### Visual of Learned Templates
  <div align="center">
  <img src="https://user-images.githubusercontent.com/5456665/27283437-1a69706c-5516-11e7-9410-cf169d325a43.png" height="500" width=auto title="Template Knowledge">
  </div>

### Downloads
- [AlphabetRecognizer (zip)](https://github.com/MinhasKamal/AlphabetRecognizer/archive/master.zip)
- [English Alphabet Dataset (zip)](https://github.com/MinhasKamal/AlphabetRecognizer/files/1084725/English.Alphabet.Dataset.zip)

If you like this project, you may also like [GenderRecognizer- Plain Face Detector & Gender Recognizer](https://github.com/MinhasKamal/GenderRecognizer) and [SkinDetector- Detects Human Skin From Image](https://github.com/MinhasKamal/SkinDetector).

### License

<a rel="license" href="https://opensource.org/licenses/MIT"><img alt="MIT License" src="https://cloud.githubusercontent.com/assets/5456665/18950087/fbe0681a-865f-11e6-9552-e59d038d5913.png" width="60em" height=auto/></a><br/><a href="https://github.com/MinhasKamal/AlphabetRecognizer">Alphabet Recognizer</a> project and its <a href="https://github.com/MinhasKamal/AlphabetRecognizer/tree/master/src/res/trainingData">Training Dataset</a> is licensed under <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
