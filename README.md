# kick-website-endpoints
## A list of known endpoints of kick.com. (Open a pull request to add or remove some.)
Links:
- https://kickbot.gg?utm_source=github-kick-endpoints
- https://sattler.dev?utm_source=github-kick-endpoints

GET documentation

GET docs/{jsonFile?}

GET docs/asset/{asset}

GET api/oauth2-callback

GET stripe/payment/{id}

POST stripe/webhook

POST nova/login

GET nova/logout

GET nova/password/reset

POST nova/password/email

GET nova/password/reset/{token}

POST mobile/token

GET login

POST logout

GET register

GET password/reset

POST password/email

GET password/reset/{token}

POST password/reset

GET password/confirm

POST socialite/{provider}

GET api/v1/user

GET api/v1/resource-urls

POST api/v1/signup/agreed-terms

POST api/v1/signup/username

POST api/v1/signup/complete

POST api/v1/signup/verification/resend

POST api/v1/signup/send/sms

POST api/v1/signup/send/email

POST api/v1/signup/verify/code

POST api/v1/signup/verify/email

POST api/v1/signup/verify/username

POST api/v1/signup/verify/phone

GET kick-token-provider

GET channels/check-username/{username}

GET api/search

GET nova/terms

GET api/v1/channels/{channel}/chat

GET api/v1/channels/followed

POST api/v1/channel-links/reorder

POST api/v1/message-react

POST api/v1/channels/{channel}/mute-user

GET api/v1/channels/{channel}/followers

POST api/v1/channels/{channel}/add-badge

POST api/v1/channels/{channel}/remove-badge

GET api/v1/channels/{channel}/get-followers-for-badge/{badge}

POST api/v1/channels/{channel}/support-a-creator

GET api/v1/live-channels/{channel}/search

GET api/v1/subscriptions

GET api/v1/subscriptions/subscribers

GET api/v1/subscriptions/history

GET api/v1/subscriptions/connect-account

POST api/v1/subscriptions/connect-account

GET api/v1/subscriptions/plan

GET api/v1/subscriptions/default-payment-method

GET api/v1/subscriptions/payment-methods

POST api/v1/subscriptions/payment-methods

DELETE api/v1/subscriptions/payment-methods/{id}

GET api/v1/subscriptions/stripe-countries

GET api/v1/subscriptions/setup-intent

GET api/v1/subscriptions/reset

DELETE api/v1/subscriptions/reset

POST api/v1/subscriptions/channels/{channel}/subscribe

GET api/v1/subscriptions/payments-history

PUT api/v1/subscriptions/{subscription}/update-payment-method

DELETE api/v1/subscriptions/{subscription}

POST api/v1/subscriptions/channels/{channel}/gift-subscriptions

POST api/v1/subscriptions/channels/{channel}/confirm-payment-intent

POST api/v1/channels/user/subscribe

POST api/v1/channels/user/unsubscribe

GET api/v1/channels/{channel}/livestream

GET api/v1/live-streams/{liveStream}/heart-beat

POST api/v1/channels/{channel}/chat

POST api/v1/report-content

GET api/v1/channels/following/{id}

GET api/v1/{channel}/chatroom

PUT api/v1/chatrooms/{chatroom}

POST api/v1/chat-messages

POST api/v1/chat-messages/{id}

POST api/v1/channel-links

PUT api/v1/channel-links/{channel_link}

DELETE api/v1/channel-links/{channel_link}

GET api/v1/channels/{channel}

GET api/v1/channels/{channel}/links

GET api/v1/users/{username}

GET api/v1/categories

GET api/v1/categories/top

GET api/v1/user/categories/top

GET api/v1/categories/{category}

GET api/v1/user/livestreams

GET api/v1/subcategories

GET api/v1/listsubcategories

GET api/v1/subcategories/{subcategory}

GET api/v1/video/{video}

POST api/v1/video/views/{video}

DELETE api/v1/video/{video}

POST api/v1/subcategories/{subcategory}/toggle-follow

GET api/v1/channels/{channel}/banned-users

POST api/mobile/channels/{channel}/subscriptions

POST api/mobile/channels/{channel}/gift

GET api/v2/channels/followed

POST api/v2/channels/{channel}/subscriptions

DELETE api/v2/channels/{channel}/subscriptions

PUT api/v2/channels/{channel}/subscriptions/enable

POST api/v2/channels/{channel}/gift

GET api/v2/channels/{channel}/should-migrate

GET api/v2/channels/{channel}/migrate

POST api/v2/channels/{channel}/report

POST api/v2/channels/{channel}/polls

DELETE api/v2/channels/{channel}/polls

POST api/v2/channels/{channel}/polls/vote

POST api/v2/channels/{channel}/pinned-message

DELETE api/v2/channels/{channel}/pinned-message

GET api/v2/channels/{channel}/plans

GET api/v2/channels/{channel}/me

POST api/v2/channels/{channel}/follow

DELETE api/v2/channels/{channel}/follow

GET api/v2/user/payment-profile

POST api/v2/user/payment-methods

POST api/v2/user/payment-methods/delete

POST api/v2/user/payment-methods/default

GET api/v2/user/subscriptions

POST api/v2/channels/{channel}/chat-commands

GET api/v2/channels/{channel}/clips/init

POST api/v2/channels/{channel}/clips/finalize

DELETE api/v2/clips/{clip}

PUT api/v2/clips/{clip}/like

DELETE api/v2/clips/{clip}/like

GET api/v2/channels/{channel}/bans

POST api/v2/channels/{channel}/bans

DELETE api/v2/channels/{channel}/bans/{username}

GET api/v2/channels/{channel}/subscribers/last

POST api/v2/mobile-tokens

DELETE api/v2/mobile-tokens/{token}

PUT api/v2/channels/{channelId}/users/{userId}/identity

GET api/v2/channels/feed-activities

GET api/v2/channels/{channelId}/users/{userId}/messages

POST api/v2/security/user/update-phone

POST api/v2/stream/update

GET api/v2/user/verified-status

GET api/v2/channels/{channel}/polls

GET api/v2/channels/{channelId}/users/{userId}/identity

GET api/v2/users/{userId}/messages

GET api/v2/channels/{channelId}/messages

GET api/v2/channels/{channel}

GET api/v2/channels/{channel}/users/{username}

GET api/v2/channels/{channel}/chatroom

PUT api/v2/channels/{channel}/chatroom

GET api/v2/channels/{channel}/livestream

GET api/v2/channels/{channel}/videos/latest

GET api/v2/channels/{channel}/chatroom/rules

PUT api/v2/channels/{channel}/chatroom/rules

GET api/v2/channels/{channel}/chatroom/banned-words

PUT api/v2/channels/{channel}/chatroom/banned-words

GET api/v2/clips/{clip}

GET api/v2/channels/{channel}/clips

PUT api/v2/clips/{clip}/private

GET api/v2/clips/{clip}/info

GET api/v2/clips

GET api/v2/categories/{subcategory}/clips

GET api/v2/channels/{channel}/leaderboards

PUT api/v2/livestreams/{liveStream}/mature

POST api/v2/messages/send/{chatroomId}

DELETE api/v2/chatrooms/{chatroomId}/messages/{messageId}

POST stream/update

POST stream/{liveStream}/update

GET stream/info

PUT stream/info

GET stream/publish_token

PUT channels

POST channels/add-user

POST channels/remove-user

PUT emotes/prefix

GET emotes

POST emotes

DELETE emotes/{emote}

GET channel-subscriber-badges

POST channel-subscriber-badges

PUT channel-subscriber-badges/{channel_subscriber_badge}

DELETE channel-subscriber-badges/{channel_subscriber_badge}

GET setup-2fa

POST verify-2fa

PUT remove-2fa

GET stream/languages

GET profile/default-pictures

PATCH profile/update-default-profile-picture

PATCH profile/update-default-banner-picture

GET emotes/{channel}

GET stream/livestreams/{lang}

GET stream/featured-livestreams/{lang}

GET current-viewers

GET featured-livestreams/non-following

POST update_profile

POST update_password

POST profile/update-profile-picture

POST profile/update-profile-banner

PATCH profile/update-notifications

PATCH profile/update-username

PATCH profile/update-offline-banner-picture

GET channels/{channel}/{username}

PUT api/internal/v1/channels/{channel}/chatroom/settings

GET api/internal/v1/channels/{channel}/chatroom/banned-words

POST api/internal/v1/channels/{channel}/chatroom/banned-words

PUT api/internal/v1/channels/{channel}/chatroom/banned-words/{bannedword}

DELETE api/internal/v1/channels/{channel}/chatroom/banned-words/{bannedword}

PUT api/internal/v1/channels/{channel}/chatroom/rules

PUT api/internal/v1/channels/{channel}/chatroom/identity

PUT api/internal/v1/chatroom/identity

POST api/internal/v1/channels/{channel}/chatroom/pinned-message

DELETE api/internal/v1/channels/{channel}/chatroom/pinned-message

POST api/internal/v1/channels/{channel}/chatroom/poll

DELETE api/internal/v1/channels/{channel}/chatroom/poll

POST api/internal/v1/channels/{channel}/chatroom/poll/vote

GET api/internal/v1/channels/{channel}/community/moderators

POST api/internal/v1/channels/{channel}/community/moderators

DELETE api/internal/v1/channels/{channel}/community/moderators/{moderator}

GET api/internal/v1/user/moderators

GET api/internal/v1/channels/{channel}/community/ogs

POST api/internal/v1/channels/{channel}/community/ogs

DELETE api/internal/v1/channels/{channel}/community/ogs/{og}

GET api/internal/v1/channels/{channel}/community/vips

POST api/internal/v1/channels/{channel}/community/vips

DELETE api/internal/v1/channels/{channel}/community/vips/{vip}

GET api/internal/v1/channels/{channel}/events

GET api/internal/v1/channels/{channel}/events/livestreams

GET api/internal/v1/chatrooms/{chatroom}/events

GET api/internal/v1/livestreams/{livestream}/events

GET api/internal/v1/channels/{channel}/chatroom

GET api/internal/v1/channels/{channel}/chatroom/settings

GET api/internal/v1/channels/{channel}/chatroom/users/{userId}/identity

GET api/internal/v1/chatroom/users/{userId}/identity

GET api/internal/v1/channels/{channel}/chatroom/rules

GET api/internal/v1/channels/{channel}/chatroom/pinned-message

GET api/internal/v1/channels/{channel}/chatroom/poll

POST webhooks/sns

POST redirect/{provider}

GET sitemap

GET legal/{page}

GET email/verify/{id}/{hash}

GET payment-intent-redirect

GET verify-new-email/{token}

GET documentation/api-docs.json

GET nova-impersonate/users/{id}/{guardName?}

GET nova-impersonate/leave

GET nova-vendor/maatwebsite/laravel-nova-excel/download

GET nova

GET {fallbackPlaceholder}

