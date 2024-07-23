# برنامه لاگین ساده با فلاسک

این یک برنامه ساده فرم لاگین است که با پایتون و فلاسک ساخته شده است. این برنامه مفاهیم پایه توسعه وب را نشان می‌دهد و می‌تواند به عنوان نقطه شروعی برای یادگیری تست نفوذ برنامه‌های وب مورد استفاده قرار گیرد.

## ویژگی‌ها

- **فرم لاگین ساده**: امکان وارد کردن نام کاربری و رمز عبور
- **احراز هویت پایه**: بررسی اعتبار کاربر با مقادیر ثابت
- **نصب و راه‌اندازی آسان**: قابلیت اجرا به صورت محلی

## پیش‌نیازها

- **پایتون**: نصب پایتون از [python.org](https://www.python.org/)
- **پکیج منیجر پایتون (pip)**: برای نصب وابستگی‌ها

## نصب و راه‌اندازی

1. **کپی فایل‌ها**: ابتدا فایل‌های پروژه را روی سیستم خود کپی کنید.

2. **ایجاد محیط مجازی**:

   ```bash
   python -m venv venv
   ```

3. **فعال‌سازی محیط مجازی**:

   - **ویندوز**:

     ```bash
     venv\Scripts\activate
     ```

   - **macOS و لینوکس**:

     ```bash
     source venv/bin/activate
     ```

4. **نصب وابستگی‌ها**:

   ```bash
   pip install flask
   ```

5. **اجرای برنامه**:

   ```bash
   python app.py
   ```

   حالا می‌توانید برنامه را در مرورگر خود با باز کردن [http://127.0.0.1:5000/](http://127.0.0.1:5000/) مشاهده کنید.

6. **تست لاگین**:

   - نام کاربری: `admin`
   - رمز عبور: `50`

---

# Simple Flask Login App

This is a simple login form web application built with Python and Flask. It demonstrates basic web development concepts and can be used as a starting point for learning web application penetration testing.

## Features

- **Simple Login Form**: Allows users to enter a username and password.
- **Basic Authentication**: Checks user credentials against hardcoded values.
- **Easy to Set Up**: Can be run locally with minimal dependencies.

## Prerequisites

- **Python**: Make sure Python is installed on your machine. You can download it from [python.org](https://www.python.org/)
- **Python Package Manager (pip)**: To install dependencies.

## Installation

1. **Clone the Files**: First, copy the project files to your system.

2. **Create a Virtual Environment**:

   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:

   ```bash
   pip install flask
   ```

5. **Run the Application**:

   ```bash
   python app.py
   ```

   Now, you can view the application in your browser by opening [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

6. **Test the Login**:

   - Username: `admin`
   - Password: `50`
