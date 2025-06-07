# 📱 FinancePick!

## Introduction

### A friendly and easy-to-use economic information app for beginner investors

[FinancePick!]is an **AI-based learning app** designed to help beginner investors easily understand economic concepts through features like **economic news summaries, glossary explanations, and quizzes**.  
By utilizing OpenAI's chatbot and summarization features, the app lowers the barrier to economic information and promotes fun and efficient learning.  
Built with Flutter, it supports both Android and iOS, and includes features like a personalized vocabulary book and a My Page section.

## Team

| Jaehun Jang [@ContinueUser02](https://github.com/ContinueUser02) <br/>| Seokhyun Lim [@ssklim](https://github.com/ssklim) <br/>| Hyunjung Shim [@gangmaru](https://github.com/gangmaru) <br/>| Soyeong Kwon [@ksy0725](https://github.com/ksy0725) 

## Tech Stack

<table>
<thead>
<tr>
<th>Category</th>
<th>Tech Stack</th>
</tr>
</thead>
<tbody>
<tr>
<td>Frontend</td>
<td>
<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
</td>
</tr>
<tr>
<td>Backend</td>
<td>
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/jwt-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
<img src="https://img.shields.io/badge/oauth2-EB5424?style=for-the-badge&logo=oauth&logoColor=white">
</td>
</tr>
<tr>
<td>AI</td>
<td>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
</td>
</tr>
<tr>
<td>Infrastructure / Collaboration</td>
<td>
<img src="https://img.shields.io/badge/OCI-F80000?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
</td>
</tr>
</tbody>
</table>

## Development Environment

### Frontend

- Framework: Flutter
- State Management: Provider
- Networking: Dio
- Platform: Android / iOS

### Backend

- Framework: Spring Boot
- Security: JWT, OAuth2 (Google)
- Database: MySQL
- API: RESTful
- News Crawling: Python + Naver News API

### AI

- OpenAI GPT API
  - News summarization
  - Glossary explanations
  - Quiz generation

## Key Features

- 📢 **Filtered economic news delivery**
- 📝 **News summarization with OpenAI**
- 🤖 **Glossary chatbot powered by GPT**
- 📌 **Daily popup word for repeated learning**
- 🧠 **Economic quizzes**
- 📚 **Vocabulary book feature**
- 👤 **User authentication system**

## System Architecture

```
User
  ↓
Flutter App (Mobile)
  ↓
Spring Boot Backend API
  ├── User/Auth (JWT, OAuth2)
  ├── News + Crawling (Naver API + Python)
  ├── GPT Integration (OpenAI)
  └── MySQL (User, News, Quiz, Words)
```

## Getting Started

```bash
git clone https://github.com/FinancePick/FinancePick-FE.git
cd FinancePick-FE
flutter pub get
flutter run
```

## .env Configuration

```
OPENAI_API_KEY=your_openai_key
NAVER_CLIENT_ID=your_naver_id
NAVER_SECRET=your_naver_secret
```

## License

© 2025 Team FinancePick. All rights reserved.
