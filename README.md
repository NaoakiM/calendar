# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# アプリケーション名

calendar

# アプリケーション概要

予定をカレンダーの日付に入力できるアプリ

# 利用方法

確定している予定をタイトル欄に入力し、Create Blogをクリックすると予定がカレンダー内に入る

# 実装した機能についての画像

https://gyazo.com/be61decd476492a1433d77dd1fb79414
https://gyazo.com/f6b9d6318fe145184b6eb5ab6ef95412

# テーブル設計

## users テーブル

| Column             | Type   | Options                   |
| ------------------ | ------ | -----------               |
| nickname           | string | null: false               |
| email              | string | null: false, unique: true |
| encrypted_password | string | null: false               |
| last_name          | string | null: false               |
| first_name         | string | null: false               |
| last_name_kana     | string | null: false               |
| first_name_kana    | string | null: false               |
| user_birth_date    | date   | null: false               |
