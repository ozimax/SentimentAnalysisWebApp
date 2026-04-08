# SentimentAnalysisWebApp
Sample ASP.NET Core Razor Pages application that classifies sentiment from website comments in real time

### Sentiment Analysis Web App

An **ASP.NET Core Razor Pages** application that performs real-time sentiment analysis on website comments. The project leverages **ML.NET** and was developed using **Model Builder** to classify comments as either toxic or non-toxic based on a Wikipedia detox dataset.

---

### Key Features
* **Real-Time Classification:** Instantly predicts sentiment (Positive/Negative) as the user types or submits a comment.
* **ML.NET Integration:** Uses a custom-trained model built with a `.tsv` dataset.
* **Thread-Safe Inference:** Implements `PredictionEnginePool` to ensure high performance and stability in a web environment.
* **Modern .NET Stack:** Built with Razor Pages and Dependency Injection for clean, maintainable code.

---

### Getting Started
1. **Clone the repo:** `git clone <your-url>`
2. **Restore Packages:** `dotnet restore`
3. **Run the App:** `dotnet run` (The app will be available at `https://localhost:5001`)

---

### Model Details
* **Dataset:** `wikipedia-detox-250-line-data.tsv`
* **Task:** Binary Classification
* **Tooling:** ML.NET Model Builder (Visual Studio)
