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

## creditcardテーブル
|Column|Type|Options|
|------|----|-------|
|Column|Type|Options|
|card_id|text|null: false|
|user_id|references|null: false, foreign_key: true|
### Association
- belongs_to :user

## tweetテーブル
|Column|Type|Options|
|------|----|-------|
|name|string|       |
|text|string|       |
|imag|text|         |