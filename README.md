# 📝 Catatan Sederhana - Simple Notes Application

<p align="center">
<a href="https://github.com/rafifpurnomo/website-catatan-sederhana-dev/actions"><img src="https://github.com/rafifpurnomo/website-catatan-sederhana-dev/workflows/PHPUnit%20Tests%20-%20Catatan%20Sederhana/badge.svg" alt="Tests Status"></a>
<a href="https://github.com/rafifpurnomo/website-catatan-sederhana-dev"><img src="https://img.shields.io/badge/PHP-8.2%20%7C%208.3-blue" alt="PHP Version"></a>
<a href="https://github.com/rafifpurnomo/website-catatan-sederhana-dev"><img src="https://img.shields.io/badge/Laravel-11.x-red" alt="Laravel Version"></a>
<a href="https://github.com/rafifpurnomo/website-catatan-sederhana-dev/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="License"></a>
</p>

## 👥 Tim Pengembang

**Testing Team:**
- Rafif Purnomo
- Reihan Ramadhana
- Zidan Syifa Fajar
- Naufal Ammar
- Irji Syahrul

## 🚀 Tentang Aplikasi

Catatan Sederhana adalah aplikasi web berbasis Laravel untuk mencatat dan mengelola catatan pribadi. Aplikasi ini dilengkapi dengan testing otomatis menggunakan PHPUnit dan CI/CD dengan GitHub Actions.

### ✨ Fitur Utama
- ✅ Membuat catatan baru
- ✅ Membaca/melihat catatan
- ✅ Mengupdate catatan
- ✅ Menghapus catatan
- ✅ Automated Testing dengan PHPUnit
- ✅ CI/CD dengan GitHub Actions

## 🧪 Testing

Aplikasi ini menggunakan **PHPUnit** untuk automated testing dengan coverage minimum 80%.

### Menjalankan Tests

```bash
# Semua tests
php artisan test

# Unit tests saja
php artisan test --testsuite=Unit

# Feature tests saja
php artisan test --testsuite=Feature

# Dengan coverage
php artisan test --coverage --min=80
```

📖 **Dokumentasi lengkap testing**: Lihat [TESTING.md](TESTING.md)

## 🔄 CI/CD Pipeline

Setiap push atau pull request ke branch `main` atau `develop` akan otomatis menjalankan:
- ✅ PHPUnit tests pada PHP 8.2 dan 8.3
- ✅ Unit dan Feature tests
- ✅ Code coverage analysis
- ✅ Upload test artifacts

## 🛠️ Teknologi yang Digunakan

- **Framework**: Laravel 11.x
- **PHP**: 8.2 | 8.3
- **Database**: SQLite (testing), MySQL/PostgreSQL (production)
- **Testing**: PHPUnit
- **CI/CD**: GitHub Actions

---

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework. You can also check out [Laravel Learn](https://laravel.com/learn), where you will be guided through building a modern Laravel application.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
