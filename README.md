# Feplace

A modern mobile application with a Python/FastAPI backend.

## Project Structure

```
./
├── mobile/        (Flutter mobile app)
│   ├── android/   (Android specific files)
│   ├── ios/       (iOS specific files)
│   ├── lib/       (Dart source code)
│   └── test/      (Flutter tests)
│
├── backend/       (Python/FastAPI backend)
│   ├── main.py    (Main application file)
│   ├── routers/   (API route handlers)
│   ├── models/    (Data models)
│   ├── database/  (Database configuration)
│   └── security/  (Authentication & authorization)
│
└── documentation/ (Project documentation)
```

## Setup Instructions

### Backend Setup

1. Create a virtual environment:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the development server:
```bash
uvicorn main:app --reload
```

### Mobile App Setup

1. Install Flutter SDK from [flutter.dev](https://flutter.dev)

2. Install dependencies:
```bash
cd mobile
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Development

- Backend API documentation will be available at `http://localhost:8000/docs` when running the server
- Mobile app development can be done using Android Studio or VS Code with Flutter extensions

## Contributing

Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.