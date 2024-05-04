# TTTこどもプログラミング教室岡山校用p5.js教材
p5.js教材サイトのフロントエンドリポジトリです
## 技術スタック
- フロントエンド
    - Next.js(当リポジトリ)
- バックエンド
    - Ruby on Rails
## デプロイ先
- フロントエンド
    - Vercel
    - [URL](https://ttt-games.vercel.app)
- バックエンド
    - Heroku
    - [URL](https://backend-ttt-games-e03fa5aec993.herokuapp.com/api/v1/health_check)

## 画面
### 教材一覧
![教材一覧画面](https://takokke-github-images.s3.ap-northeast-1.amazonaws.com/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-05-04%2013.27.33.png?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaDmFwLW5vcnRoZWFzdC0xIkgwRgIhAPbKo0HqhUq2BxQX%2Fpb1TUhhQeX9AdCfSrRuvLEkODGkAiEA1NKPxKFzoHrgwD4hHDuv2hm8E0ln20Vf%2FoawTXrNkc0q7QIIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw3NjA0MjYyMTkyODIiDPahTWMgyeuDk3eNAyrBAqkb49efqpU2pJp39C7%2F3nSmwK81CbhxQcJxHRf9sd2Olw%2BOJAPE9ufe3FiqXds82Qn9b0wuchrqzjxLupNy9FNhZJ5Quf4xdoYMTzPxKZQPaSk6eSvO%2FSAf00yoBKR4OHUcZ2MF4o7YLGzoPdGGh0B5wK4zuwlmavn%2FbhAebRN55%2BLT4ezqUY08pdNs%2FQY80LaxcgTfXF%2FTOu3h%2FkzX4rYGgVYa0WuvvxjDqNdnDOZJ64bokMZwRtxlBnnJxp7Bhy9IwjOYyLliPVUPV5X5B7EfZSGI15RX0R9WHUoY%2FpCiEZL1CEQYN%2BRVlFtQkas%2FwU%2B%2F1zbxfrS7MY8P%2FstElsWGxgZmQSgl%2B3iMY4rmJtxpFvdENY8t2npRzZP8vx23DT437kt9ep42e9hPezGTlP54m2q8G%2BxAJdUiSjaJCTVYLzDS79axBjqyArE9BbivZoya6DrKdUvwrGX5czAWNue3nRfN7wVHEVpGmzoq3XGV7TSlYYnZguakbl1cdxgqVFHGP0BGqavcIGes%2B0Y6hNSn7CiHGui5pa%2B37RR0smy1QPF1fUf%2BjBfW22ZQRstxkreULVy3sprMhK66zSXbGFo1h9%2Bpsd0fRH6PPl03zrT1BWp1vrb%2FFI7LEOn%2BfzNnwLtL6klAnHKX1LFYPm30JmqU72w9LIS2ZDB9YcGkJavE4kpyDW1OY7nahK43hyhZ0Vju3ouu67kJ53T7ComgTF9rzhM%2BHMDLvdxWNH%2FBZGuAwROhrmjhuuNZkX6RbH4qsjL9gYZt7qrEBQmk5x8D%2BunTXQm5ZWxoD6YHRFP%2FklFuUiU3UK%2FWrqk8xBMig8t%2BQXcuwVE%2FcdE4GMS9Mg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240504T042813Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA3CDHPI4JN7B3CP47%2F20240504%2Fap-northeast-1%2Fs3%2Faws4_request&X-Amz-Signature=dab91b315a59e108b069e15029cafe518478b197f665d86c6394c1c95d6263fa)

### 教材詳細
![教材詳細画面](https://takokke-github-images.s3.ap-northeast-1.amazonaws.com/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-05-02%2014.55.03.png?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaDmFwLW5vcnRoZWFzdC0xIkgwRgIhAPbKo0HqhUq2BxQX%2Fpb1TUhhQeX9AdCfSrRuvLEkODGkAiEA1NKPxKFzoHrgwD4hHDuv2hm8E0ln20Vf%2FoawTXrNkc0q7QIIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw3NjA0MjYyMTkyODIiDPahTWMgyeuDk3eNAyrBAqkb49efqpU2pJp39C7%2F3nSmwK81CbhxQcJxHRf9sd2Olw%2BOJAPE9ufe3FiqXds82Qn9b0wuchrqzjxLupNy9FNhZJ5Quf4xdoYMTzPxKZQPaSk6eSvO%2FSAf00yoBKR4OHUcZ2MF4o7YLGzoPdGGh0B5wK4zuwlmavn%2FbhAebRN55%2BLT4ezqUY08pdNs%2FQY80LaxcgTfXF%2FTOu3h%2FkzX4rYGgVYa0WuvvxjDqNdnDOZJ64bokMZwRtxlBnnJxp7Bhy9IwjOYyLliPVUPV5X5B7EfZSGI15RX0R9WHUoY%2FpCiEZL1CEQYN%2BRVlFtQkas%2FwU%2B%2F1zbxfrS7MY8P%2FstElsWGxgZmQSgl%2B3iMY4rmJtxpFvdENY8t2npRzZP8vx23DT437kt9ep42e9hPezGTlP54m2q8G%2BxAJdUiSjaJCTVYLzDS79axBjqyArE9BbivZoya6DrKdUvwrGX5czAWNue3nRfN7wVHEVpGmzoq3XGV7TSlYYnZguakbl1cdxgqVFHGP0BGqavcIGes%2B0Y6hNSn7CiHGui5pa%2B37RR0smy1QPF1fUf%2BjBfW22ZQRstxkreULVy3sprMhK66zSXbGFo1h9%2Bpsd0fRH6PPl03zrT1BWp1vrb%2FFI7LEOn%2BfzNnwLtL6klAnHKX1LFYPm30JmqU72w9LIS2ZDB9YcGkJavE4kpyDW1OY7nahK43hyhZ0Vju3ouu67kJ53T7ComgTF9rzhM%2BHMDLvdxWNH%2FBZGuAwROhrmjhuuNZkX6RbH4qsjL9gYZt7qrEBQmk5x8D%2BunTXQm5ZWxoD6YHRFP%2FklFuUiU3UK%2FWrqk8xBMig8t%2BQXcuwVE%2FcdE4GMS9Mg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240504T042507Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA3CDHPI4JN7B3CP47%2F20240504%2Fap-northeast-1%2Fs3%2Faws4_request&X-Amz-Signature=207007e5bb611f0f67489851913dcb266972eaa65b02173b0a6bcb10b7b19d97)

### 教材作成
![教材作成画面](https://takokke-github-images.s3.ap-northeast-1.amazonaws.com/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-05-04%2013.29.18.png?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaDmFwLW5vcnRoZWFzdC0xIkgwRgIhAPbKo0HqhUq2BxQX%2Fpb1TUhhQeX9AdCfSrRuvLEkODGkAiEA1NKPxKFzoHrgwD4hHDuv2hm8E0ln20Vf%2FoawTXrNkc0q7QIIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw3NjA0MjYyMTkyODIiDPahTWMgyeuDk3eNAyrBAqkb49efqpU2pJp39C7%2F3nSmwK81CbhxQcJxHRf9sd2Olw%2BOJAPE9ufe3FiqXds82Qn9b0wuchrqzjxLupNy9FNhZJ5Quf4xdoYMTzPxKZQPaSk6eSvO%2FSAf00yoBKR4OHUcZ2MF4o7YLGzoPdGGh0B5wK4zuwlmavn%2FbhAebRN55%2BLT4ezqUY08pdNs%2FQY80LaxcgTfXF%2FTOu3h%2FkzX4rYGgVYa0WuvvxjDqNdnDOZJ64bokMZwRtxlBnnJxp7Bhy9IwjOYyLliPVUPV5X5B7EfZSGI15RX0R9WHUoY%2FpCiEZL1CEQYN%2BRVlFtQkas%2FwU%2B%2F1zbxfrS7MY8P%2FstElsWGxgZmQSgl%2B3iMY4rmJtxpFvdENY8t2npRzZP8vx23DT437kt9ep42e9hPezGTlP54m2q8G%2BxAJdUiSjaJCTVYLzDS79axBjqyArE9BbivZoya6DrKdUvwrGX5czAWNue3nRfN7wVHEVpGmzoq3XGV7TSlYYnZguakbl1cdxgqVFHGP0BGqavcIGes%2B0Y6hNSn7CiHGui5pa%2B37RR0smy1QPF1fUf%2BjBfW22ZQRstxkreULVy3sprMhK66zSXbGFo1h9%2Bpsd0fRH6PPl03zrT1BWp1vrb%2FFI7LEOn%2BfzNnwLtL6klAnHKX1LFYPm30JmqU72w9LIS2ZDB9YcGkJavE4kpyDW1OY7nahK43hyhZ0Vju3ouu67kJ53T7ComgTF9rzhM%2BHMDLvdxWNH%2FBZGuAwROhrmjhuuNZkX6RbH4qsjL9gYZt7qrEBQmk5x8D%2BunTXQm5ZWxoD6YHRFP%2FklFuUiU3UK%2FWrqk8xBMig8t%2BQXcuwVE%2FcdE4GMS9Mg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240504T042942Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA3CDHPI4JN7B3CP47%2F20240504%2Fap-northeast-1%2Fs3%2Faws4_request&X-Amz-Signature=de3e76ee54cabee57480fa877af277ae2e4711c240928696a0fd453385a6080b)

### 記事管理画面
![管理画面](https://takokke-github-images.s3.ap-northeast-1.amazonaws.com/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-05-04%2013.32.47.png?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaDmFwLW5vcnRoZWFzdC0xIkgwRgIhAPbKo0HqhUq2BxQX%2Fpb1TUhhQeX9AdCfSrRuvLEkODGkAiEA1NKPxKFzoHrgwD4hHDuv2hm8E0ln20Vf%2FoawTXrNkc0q7QIIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw3NjA0MjYyMTkyODIiDPahTWMgyeuDk3eNAyrBAqkb49efqpU2pJp39C7%2F3nSmwK81CbhxQcJxHRf9sd2Olw%2BOJAPE9ufe3FiqXds82Qn9b0wuchrqzjxLupNy9FNhZJ5Quf4xdoYMTzPxKZQPaSk6eSvO%2FSAf00yoBKR4OHUcZ2MF4o7YLGzoPdGGh0B5wK4zuwlmavn%2FbhAebRN55%2BLT4ezqUY08pdNs%2FQY80LaxcgTfXF%2FTOu3h%2FkzX4rYGgVYa0WuvvxjDqNdnDOZJ64bokMZwRtxlBnnJxp7Bhy9IwjOYyLliPVUPV5X5B7EfZSGI15RX0R9WHUoY%2FpCiEZL1CEQYN%2BRVlFtQkas%2FwU%2B%2F1zbxfrS7MY8P%2FstElsWGxgZmQSgl%2B3iMY4rmJtxpFvdENY8t2npRzZP8vx23DT437kt9ep42e9hPezGTlP54m2q8G%2BxAJdUiSjaJCTVYLzDS79axBjqyArE9BbivZoya6DrKdUvwrGX5czAWNue3nRfN7wVHEVpGmzoq3XGV7TSlYYnZguakbl1cdxgqVFHGP0BGqavcIGes%2B0Y6hNSn7CiHGui5pa%2B37RR0smy1QPF1fUf%2BjBfW22ZQRstxkreULVy3sprMhK66zSXbGFo1h9%2Bpsd0fRH6PPl03zrT1BWp1vrb%2FFI7LEOn%2BfzNnwLtL6klAnHKX1LFYPm30JmqU72w9LIS2ZDB9YcGkJavE4kpyDW1OY7nahK43hyhZ0Vju3ouu67kJ53T7ComgTF9rzhM%2BHMDLvdxWNH%2FBZGuAwROhrmjhuuNZkX6RbH4qsjL9gYZt7qrEBQmk5x8D%2BunTXQm5ZWxoD6YHRFP%2FklFuUiU3UK%2FWrqk8xBMig8t%2BQXcuwVE%2FcdE4GMS9Mg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240504T043331Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA3CDHPI4JN7B3CP47%2F20240504%2Fap-northeast-1%2Fs3%2Faws4_request&X-Amz-Signature=fcc2c76257949a4682f5e242fe2ae6e80a21b1ca9d0ecdc24ebb99328a454e5c)