# 🌦️ MausamNama - Your Daily Weather Companion

Live: [https://mausamnama.netlify.app](https://mausamnama.netlify.app)

**MausamNama** is a modern and responsive weather forecasting web application built using **Vite**, **React**, **TypeScript**, and **TailwindCSS**. It fetches real-time weather data and 5-day forecasts using the OpenWeatherMap API and provides a sleek user experience for weather tracking.

## 🔧 Tech Stack

- ⚡ Vite
- ⚛️ React
- 🟦 TypeScript
- 💨 TailwindCSS
- 🌐 Weather API

## 📦 Getting Started

Clone the project and install dependencies:

```bash
git clone https://github.com/your-username/mausamnama.git
cd mausamnama
npm install
```

Run the development server:

```bash
npm run dev
```

## 🔐 Environment Variables

Create a `.env` file in the root folder and add your API key like this:

```
VITE_WEATHER_API_KEY=your_api_key_here
```

## 🚀 Deployment

This project is deployed using **Netlify**. Make sure to add your environment variable (`VITE_WEATHER_API_KEY`) in Netlify's Site Settings under **Environment Variables**.

## 📁 Folder Structure

```
src/
  ├── api/            # API utilities like weatherService.ts
  ├── components/     # Reusable UI components
  ├── assets/         # Images, icons, etc.
  ├── App.tsx         # Main app component
  └── main.tsx        # Entry point
```

## 🙌 Contributing

Feel free to fork the repo and submit a pull request if you have suggestions or improvements!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

