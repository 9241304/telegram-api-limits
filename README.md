### Telegram API requests limits
#### Messaging
1. 1 request per 1 second to the same user (official), 5 requests per 1 second (unofficial)
2. ~30 requests to different users per 1 second, combining with 1 (**not checked**)
3. 20 requests per group chat/channel per 60 seconds (official), combining with 5 requests per 5 seconds (**undocumented**)
4. Unlimited **reply** requests to users, looks like combining with 1 (unofficial), 2
5. Unknown limits for forums, possibly the same as for channels (**not checked**)
#### Other
1. 30 requests per 30 seconds, not combining with anything (**undocumented**)
