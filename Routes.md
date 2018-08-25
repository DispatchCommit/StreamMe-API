`GET` `/api-user/v1/{userSlug}/channel`

`GET` `/api-actor/v2/rooms/{chatroomId}/role-info`

`GET` `/api-multistream/v1/multistreams/{multistreamPublicId}`

`GET` `/api-multistream/v1/users/{userPublicId}`

`GET` `/api-chat/v2/rooms/{chatroomId}/roster`

`GET` `/api-vod/v1/{userSlug}/archives?playable=true`

`GET` `/api-channel/v1/channels?publicIds={userPublicId},{userPublicId}`

`GET` `/api-chat/v1/user/{userPublicId}/preferences`

`GET` `/api-chat/v1/rooms/{chatroomId}/preferences`

`GET` `/api-commands/v1/room/{chatroomId}/command/history`

`GET` `/api-chat/v1/rooms/{chatroomId}/poll`

`GET` `/api-user/v2/{userSlug}/app/web/channel/updates?requestedLocale=en`

`GET` `/api-stickers/v1/users/7{userPublicId}/stickers`

`GET` `/api-note/v1/users/{userSlug}/notes?filter=new`

`GET` `/api-note/v1/users/{userSlug}/notes/new-count`

`GET` `/api-subscribe/v1/users/{userPublicId}/subscribed/{streamerPublicId}/sub-anniversary-status`

`GET` `/api-search/v2/complete/users?q={query}`

`GET` `/api-panel/v1/users/{userPublicId}/panels`

`GET` `/api-emoticon/v3/{userSlug}/manage`

`GET` `/api-emoticon/v1/store/points`

`GET` `/api-emoticon/v1/store/coins`

`GET` `/api-contest/v1/contests/{contestPublicId}/leaderboard`

`POST` `/api-chat/v1/user/{userPublicId}/purchase/color/{productId}`

`POST?` `/api-emoticon/v1/users/{userPublicId}/purchase/{currencyType}/unlock/{emoticonId}`

`POST?` `/api-emoticon/v1/users/{userPublicId}/purchase/{currencyType}/slot/{type}`

`GET?` `/api-emoticon/v1/store/{currencyType}`

`GET` `/api-emoticon/v3/{userSlug}/manage`

`GET` `/api-fiat/v1/users/{userPublicId}/{unknown}/balance`

`GET` `/api-products/v1/{currencyType}/{packageId}?paymentGateway={paymentGateway}`

`GET?` `/api-products/v1/invoices/{invoiceId}/status`

`PUT` `/api-user/v1/{userSlug}/theme` `{ theme: "{themeName}" }`

`GET` `/api-view/media/{unknown}?source=channel`

`GET` `/api-chat/v1/user/{userPublicId}/store/color?supporter=1&subscriber=1`

`GET` `/api-user/v1/{userPublicId}/following`

`GET` `/api-user/v1/{userPublicId}/followers`

`GET` `/api-subscribe/v1/users/{userPublicId}/subscribers`

`GET` `/api-subscribe/v1/users/{userPublicId}/subscriptions`

`GET` `/api-user/v1/{userPublicId}/supporters`

`GET` `/api-user/v1/users/{userPublicId}/channel`

`GET` `/api-user/v1/{userSlug}/channel`

`PUT` `/api-note/v1/users/{userSlug}/notes/{noteId}`

`POST` `/api-message/v1/users/{userSlug}/public-messages/{msgId}/repost` `{ userSlug: "", msgId: "" }`

`POST` `/api-message/v1/users/{userSlug}/public-messages/{msgId}/reply` `{ userSlug: "", msgId: "" }`

`POST` `/api-message/v1/users/{userSlug}/public-messages` `{ userSlug: "" }`

`GET` `/api-user/v1/{userSlug}/app/{appSlug}/channel`

`GET` `/api-live/v1/stream/{userPublicId}`

`GET` `/api-tournaments/v1/tournaments`

`GET` `/api-web/v1/chat/room/{chatroomId}`

`GET` `/api-realtime-profile/v1/users/{userSlug}/profiles/{profileId}/settings/chat`

`GET` `/api-user/v1/me`

`PUT` `/api-chat/v1/rooms/{chatroomId}/user/{userPublicId}/user-color?appSlug={platform}` `{ colorId: {colorInt} }`

`GET` `/api-web/v1/chat/commands`

`GET` `/api-search/v2/complete/tags?q={query}`

`GET` `/api-chat/v1/rooms/{chatroomId}/mention-complete?q={query}`

`PUT` `/api-poll/v1/poll/{pollId}/vote/{pollAnswerId?}`

`PUT` `/api-poll/v1/poll/{pollId}/end`

`PUT` `/api-commands/v1/room/{chatroomId}/command/unpoll/{pollId}"`

`POST` `/api-poll/v1/poll` `{ pollType: "permissive", question: "{question}", answers: {unknown[]?}, expireMinutes: {minutes}, roomPublicId: {chatroomId} }`

`GET` `/api-chat/v2/rooms/{chatroomId}/roster-audit`

`PUT` `/api-user/v1/{userPublicId}/follow/{toFollowPublicId}`

`DELETE` `/api-user/v1/{userPublicId}/follow/{toUnfollowPublicId}`

`GET` `/api-web/v2/chat/user-card/{unknown}/{userPublicId}`

`PUT` `/api-online/v1/users/{userId?}/whisper` `{ whisperStatus: {status} }`

`POST` `/api-log/v1/player-logs`

`GET` `/api-raffle/v1/rooms/{chatroomId}/raffle`

`POST` `api-seer/v1/feature/user/{unknown}/ping`

`GET` `/api-user/v1/{userPublicId?}/connections`

`PUT|DELETE` `/api-user/v1/{userSlug}/notify-preferences/web/{channelSlug}`

`GET` `/api-user/v1/{userPublicId}/stream-start-time`

`GET` `/api-live/v2/streams`


--------------

> The following commands are locked to users on the site with site-wide admin privileges, therefore they will not work unless you have proper authorization

`PUT` `/api-moderate/v1/kickstream/{userPublicId}` `{ reason: "{reason}" }`

`PUT` `/api-moderate/v1/banstream/user/{userPublicId}`

`PUT` `/api-moderate/v1/unbanstream/user/{userPublicId}`

`PUT` `/api-moderate/v1/ban/user/{userPublicId}`
