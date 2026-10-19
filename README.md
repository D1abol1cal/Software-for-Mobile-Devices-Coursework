# Software for Mobile Devices — Coursework

Flutter assignments and lab exercises from the *Software for Mobile Devices* elective, 8th semester. Each folder is a separate assignment, kept as its own Flutter project with its original commit history preserved via `git subtree`.

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)

## Assignments

| Folder | Topic |
|---|---|
| `01-first-app` | First Flutter app: a random word-pair generator |
| `02-layout-basics` | Layout widgets (Row, Column, Container, etc.) |
| `03-networking` | REST API calls with `http` |
| `04-custom-paint` | Unmodified Flutter starter template (CustomPainter work was never committed) |
| `05-animation` | Playing a Rive (`.riv`) vector animation |
| `06-battery-platform-channel` | Platform channels, reading native battery level |
| `07-todo-list` | A todo list app (local state, CRUD) |
| `08-infinite-list-bloc` | Infinite-scrolling list using the BLoC pattern |
| `09-firebase-codelab` | Firebase Auth, Firestore and realtime chat (official Firebase codelab) |

## Running any assignment

Each folder is a self-contained Flutter project:
```bash
cd 0X-folder-name
flutter pub get
flutter run
```
