# 🇩🇪 German Gender
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-blue?style=flat-square)
![Learning](https://img.shields.io/badge/Focus-Vocabulary%20%26%20Grammar-orange?style=flat-square)

## 📖 Overview

> The **German Gender** app is designed to make learning German vocabulary and grammar engaging and effective by gamifying the learning process. Initially focused on helping users learn articles (*der, die, das*) hence the name of the app, the app has grown into a comprehensive vocabulary builder with tools for practice, revision, and sentence creation.

---

## ⚡ Core Experience

### 👤 Account and Guest Modes

* **Welcome Message:** Upon launching, users see a welcome message: *“Hello, [Name],”* or *“Hello, Guest”* if not logged in.

<div align="center">
  <img src="https://github.com/user-attachments/assets/d41082ec-5424-4ba8-bf82-43cef4a73527" width="45%" /><img src="https://github.com/user-attachments/assets/b73dfceb-9672-4956-8d45-895c76b2aefd" width="45%" />
</div>

* **Offline Functionality:** The app works offline with data saved locally via SQLite. Creating an account enables data synchronization across devices and ensures that the progress will not be lost if the app is deleted.
* **Authentication:** Logging into the app requires an email and password. If an account with the specified email does not exist, the user will be redirected to a page where he is asked to enter a username in order to create a new account.

<div align="center">
  <img src="https://github.com/user-attachments/assets/210633de-d0a4-4e28-95f6-b3a17a7adb4a" width="45%" /><img src="https://github.com/user-attachments/assets/88329528-5c8b-4d4f-81ed-8e853dcec371" width="45%" />
</div>

---

## ✨ Main Features

### 📚 1. Word List

<img src="https://github.com/user-attachments/assets/ff664852-5aba-4727-88bf-113a8124902b" align="right" width="30%" />

* The place where all the progress can be seen, as well as the things that are planned for the future.
* Explore the vocabulary organized in **Nouns**, **Verbs**, **Adjectives**, **Adverbs**, **Pronouns**, **Prepositions**.
* Words are organized based on real-world frequency and display their type, subtype, translation, article if applicable and the mastery score.
* Search functionality tailored to the selected word type (e.g., *“Search noun...”*).
* **Locked words** are marked with a 🔒 padlock and can be unlocked by achieving full scores on already unlocked words in practice.

<br clear="right"/>


### 🧠 2. Revision Mode

* Flashcards for unlocked words, including translations, usage examples, and grammar highlights.
* Sentence examples with **Word Highlighting** to emphasize the target word in context, even when it appears in an inflected form (e.g., "sein" in *Ich bin müde* highlights `bin` in orange).
* Encourages mastery of words before progressing to the practice mode.
* Allows user to skip practice, but displays a ⚠️ warning.

<div align="center">
  <img src="https://github.com/user-attachments/assets/534a7d00-fb1f-41f3-af0f-5d94fe78c2ef" width="20%" /><img src="https://github.com/user-attachments/assets/e5968b86-2ee0-40ed-bd6d-3de791929765" width="20%" /><img src="https://github.com/user-attachments/assets/ed636842-dcd8-443d-937a-b352f8e59a32" width="20%" /><img src="https://github.com/user-attachments/assets/abc95f7b-98cc-44fe-a54a-e79cc4a9eced" width="20%" />
</div>

<br clear="right"/>

### 🎯 3. Practice Mode

* Users get prompted with up to **10 unlocked words** and get tested on translations, articles (for nouns), and cases (for prepositions). The selection of words prioritizes words with low scores and tries to minimize the appearance of words with large scores.
* **Dynamic hints** guide users step-by-step (e.g., *“Choose an article first”* followed by *“What is German for year?”*).

<div align="center">
  <img src="https://github.com/user-attachments/assets/9e047b06-07df-45fb-a65a-4f9a21b5076f" width="25%" /><img src="https://github.com/user-attachments/assets/b6977e63-83e4-4068-a423-9542f4221d23" width="25%" /><img src="https://github.com/user-attachments/assets/a321b16a-777e-4f15-851c-84593ec290ad" width="25%" />
</div>

* Colored progress indicators at the top of the screen show **current** (🔵 blue), **correct** (🟢 green), and **incorrect** (🔴 red) responses.
* The feedback is immediate, correct answers are highlighted in green, while errors are marked red and missing letters indicated by `?` question marks.
  
<div align="center">
  <img src="https://github.com/user-attachments/assets/71574322-65f3-4928-9b63-b7171055381f" width="25%" /><img src="https://github.com/user-attachments/assets/56beaa04-8208-4174-9eb3-29d9027660c9" width="25%" /><img src="https://github.com/user-attachments/assets/996b34e1-d448-47ff-9938-dbe21b643d0d" width="25%" />
</div>

* **Motivational messages** track streaks (e.g., *X words in a row*) and their color is dynamic to represent the size of the streak (green = low streak, yellow = medium streak, red = high streak). These messages are only displayed during the first round of practice and are not shown when retrying mistakes.
* If the user finishes the practice round and has made mistakes, he is asked if he would like to retry those words or if he would like to exit the practice round.

<div align="center">
  <img src="https://github.com/user-attachments/assets/6367d1e3-21de-4378-9ee2-0ea6cf51b572" width="25%" /><img src="https://github.com/user-attachments/assets/72f48edb-89d3-47e4-a99c-a9723fa62d3c" width="25%" /><img src="https://github.com/user-attachments/assets/f11b6d68-ff83-4688-875a-ac803c0d1330" width="25%" />
</div>

### 📊 4. Practice Statistics

* They are displayed every time the user exits a practice round. Even if they exit it before finishing it.
* Provides a summary of progress, showing score changes for each word. Negative changes in score are highlighted red, while positive ones are green.
* Newly unlocked words are displayed with a 🏆 trophy and mastered words (those where a score of `4` was reached) are displayed with a 🏆 **green trophy**.
* Words with high scores are gradually phased out to ensure focus on weaker areas.
* The score of the words will only change during the **first round** of practice and not during the retrial rounds.
* If practice is ended early, the words that were not attempted will display a blue `0` to indicate that their score was not affected.

<div align="center">
  <img alt="Screenshot_1736628664" src="https://github.com/user-attachments/assets/7cb9001b-b8e1-4a4a-932c-e2844d893526" width="45%" /><img alt="Screenshot_1736628630" src="https://github.com/user-attachments/assets/48b13ba8-7b39-46a6-af52-67e3799ae9e9" width="45%" />
</div>

### 🏗️ 5. Sentence Builder

* Use unlocked words to generate and understand sentences and their formation.
* Select the type of words you want to be used in a sentence and one word per type (noun, verb, etc.) to have a sentence automatically generated.

<div align="center">
  <img alt="Screenshot_1736628761" src="https://github.com/user-attachments/assets/bbee7aeb-a117-41ed-822e-285d185b7fe7" width="30%" /><img alt="Screenshot_1736628764" src="https://github.com/user-attachments/assets/e0d64870-0292-48bb-a3f9-36b127a34df5" width="30%" /><img alt="Screenshot_1736628772" src="https://github.com/user-attachments/assets/7f26d79f-510e-4d35-b69b-95e4a54259ee" width="30%" />
</div>

* The selected sentence components are highlighted with their own **specific color codes**. These color codes are used in the entire app, making it easier for the user to distinguish them.
* Beginner-friendly explanations below the sentence provide insights into word placement, forms, and grammatical rules.

<div align="center">
  <img alt="Screenshot_1736628786" src="https://github.com/user-attachments/assets/06f916ca-1bd8-465e-9c2a-a73b319b9a92" width="30%" /><img alt="Screenshot_1736628792" src="https://github.com/user-attachments/assets/f77cb40a-d11b-4d89-be2e-6fc29587e1c1" width="30%" /><img alt="Screenshot_1736628812" src="https://github.com/user-attachments/assets/4c9bdc3b-90fa-421f-a7e0-958b8f1f300a" width="30%" />
</div>

### 🗂️ 6. Flashcards

* Interactive flashcards display translations, word types, and relevant grammar rules.
* **Example:** For *Der Mann*, the flashcard explains *“A noun is a person, place, thing, or idea”* and includes the article's function (e.g., *Der is for masculine nouns*).

<div align="center">
  <img alt="Screenshot_1736628095" src="https://github.com/user-attachments/assets/24fbb73e-0058-4965-821a-c075486e930f" width="30%" /><img alt="Screenshot_1736628111" src="https://github.com/user-attachments/assets/c9602840-940e-4976-a509-c6cea99d0d30" width="30%" /><img alt="Screenshot_1736628101" src="https://github.com/user-attachments/assets/51928b25-89d1-4ee9-bcb5-9201a452c94a" width="30%" />
</div>

### 🏆 7. Score System

* Words are scored from `-4` to `4` based on performance.
* Achieving a score of `4` unlocks new words, and a trophy icon marks mastered words.
* Newly unlocked words get a score of `0`.
* The system encourages consistent learning by balancing repetition with progress.

---

## 🔄 Flow of Use

### 1. Revision

* Begin by reviewing unlocked words using flashcards.
* Example sentences show how words are used in context, with target words highlighted in their respective color.
* After reviewing, users can proceed to Practice or revisit missed words.

### 2. Practice

* Answer vocabulary questions, select articles (nouns), or identify cases (prepositions).
* Receive feedback on each response and track progress using visual indicators.
* Unlock new words by mastering the existing ones.

<div align="center">
  <img alt="Screenshot_1736628420" src="https://github.com/user-attachments/assets/4b754ac9-efaf-4efd-a051-b303eb2ae4f0" width="45%" /><img alt="Screenshot_1736628413" src="https://github.com/user-attachments/assets/c1059a5d-aa6a-48bf-8e7b-b843be30a590" width="45%" />
</div>

### 3. Sentence Builder

* Use unlocked words to construct sentences.
* Select one word per type, with each selection dynamically updating the list for ease of use.
* Generate sentences that maintain the selected word order and display them with translations and grammar explanations.

---

## 🚀 Technologies Used

### 📱 Mobile Application (Frontend)
* **Framework:** [React Native](https://reactnative.dev/)
* **Platform:** [Expo](https://expo.dev/) (Managed Workflow)
* **Navigation:** Custom navigation (Component-based state)
* **State Management:** React Context API (`UserContext`)
* **Styling:** `StyleSheet`, `react-native-safe-area-context`, `react-native-vector-icons`

### ☁️ Data & Backend
* **Authentication:** [Firebase Authentication](https://firebase.google.com/docs/auth)
* **Cloud Database:** [Cloud Firestore](https://firebase.google.com/docs/firestore) (for syncing user progress & unlocked words)
* **Local Database:** [SQLite](https://docs.expo.dev/versions/latest/sdk/sqlite/) (via `expo-sqlite`) used for offline storage of words and sentences.
* **Text-to-Speech:** [Expo Speech](https://docs.expo.dev/versions/latest/sdk/speech/) (`expo-speech`) for pronunciation.

### 🔄 Alternative Backend (Optional)
> The project includes a separate Node.js/Express backend located in the `backend/` directory, which uses PostgreSQL. An alternative to the Firebase implementation for users preferring a self-hosted SQL solution.

---

## 📂 Project Structure

```text
├── App.js                  # Main entry point
├── assets/                 # Images and static assets
├── backend/                # Node.js/Express backend (Alternative)
├── components/             # UI Components (Home, Practice, Stats, etc.)
├── context/                # React Context (UserContext)
├── data/                   # Static data files (wordsData.js)
├── firebase/               # Firebase configuration and helper functions
├── sqlite/                 # Local SQLite database initialization and queries
├── styles/                 # Global styles and colors
├── utils/                  # Utility functions
└── package.json            # Dependencies and scripts
