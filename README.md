<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Event Management REST API app Laravel 10

Event Management REST API App
This app is used to manage events and attendees, to create event you need to authenticate, attendees will be notified with email message 24 hours before event starts

<ul>Used Technologies:
    <li>Laravel 10</li>
    <li>PHP 8.2</li>
    <li>MySQL</li>
</ul>
<ul>Laravel Features:
    <li>Routes</li>
    <li>Models</li>
    <li>Pagination</li>
    <li>Factories and Seeder to generate data</li>
    <li>CRUD</li>
    <li>Migrations</li>
    <li>Controllers</li>
    <li>Token based authentication using Sanctum</li>
    <li>REST API</li>
    <li>Notifications</li>
    <li>Queues</li>
    <li>Task Scheduling</li>
    <li>Sending Email</li>
    <li>Authorization with Gates</li>
    <li>Authorization with Policies</li>
    <li>Signing out</li>
    <li>Rate Limiting using throttle</li>
</ul>

REST API requests

<table>
  <tr>
    <th>Collection</th>
      <th>Method</th>
    <th>Action</th>
    <th>Request</th>
  </tr>
  <tr>
    <td>Events</td>
      <td>GET</td>
    <td>Get All Events</td>
    <td>localhost:8000/events</td>
  </tr>
  <tr>
    <td>Events</td>
      <td>GET</td>
    <td>Get Single Event</td>
    <td>localhost:8000/events/1</td>
  </tr>
    <tr>
    <td>Events</td>
      <td>POST</td>
    <td>Create an Event</td>
    <td>localhost:8000/events</td>
  </tr>
    <tr>
    <td>Events</td>
      <td>DELETE</td>
    <td>Delete an Event</td>
    <td>localhost:8000/events/201</td>
  </tr>
    <tr>
    <td>Events</td>
      <td>DELETE</td>
    <td>Delete an Event</td>
    <td>localhost:8000/events/201</td>
  </tr>
</table>

To setup project run in CLI:

Clone Project:

```sh

git clone https://github.com/Yessenali-Yerkebulan/task-list-laravel.git

```

Go inside project directory:

```sh

cd task-list-laravel

```

```sh

composer install

```

```sh

cp .env.example .env

```

```sh

php artisan key:generate

```

```sh

php artisan migrate

```

after migration command select yes option to create database schema

