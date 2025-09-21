По-русски

TBotWeather — пет-проект на Go: Telegram-бот, который по названию города показывает текущую погоду из OpenWeather.
Он нормализует ввод и ищет точное совпадение (поддерживает формы Город, City, CC, City, State, CC), отсекая мусорные строки.
Технологии: Go, Telegram Bot API, OpenWeather (Geocoding + Weather).
Запуск: задать TELEGRAM_BOT_TOKEN и OPENWEATHER_API_KEY в .env, затем go run ./cmd/bot.

In English

TBotWeather is a Go pet project: a Telegram bot that shows current weather from OpenWeather by city name.
It normalizes user input and enforces exact city match (supports City, City, CC, City, State, CC) to filter out garbage inputs.
Tech stack: Go, Telegram Bot API, OpenWeather (Geocoding + Weather).
How to run: set TELEGRAM_BOT_TOKEN and OPENWEATHER_API_KEY in .env, then go run ./cmd/bot.
