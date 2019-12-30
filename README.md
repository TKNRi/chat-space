# README
## messageテーブル

|Column|Type|Options|
|------|----|-------|
|body|text|null: false|
|image|string|null: false|
|group_id|integer|
|user_id|integer|

### Association
- belongs_to :group
- belongs_to :user

