# Onlyfans profile scraper
Interested in using this scraper? Get it here: [Onlyfans profile scraper](https://apify.com/curious_coder/onlyfans-scraper?fpr=ve081&fp_sid=github_onlyfans-scraper)
## How it works
This scraper scrapes list profile urls and gives you full details including insights, social media urls, etc

✳️ **Related scrapers:** [Onlyfans posts and download links scraper](https://apify.com/curious_coder/onlyfans-post-scraper?fpr=ve081&fp_sid=github_onlyfans-scraper) | [Facebook profile scraper](https://apify.com/curious_coder/facebook-profile-scraper?fpr=ve081&fp_sid=github_onlyfans-scraper) | [Linkedin profile scraper](https://apify.com/curious_coder/linkedin-profile-scraper?fpr=ve081&fp_sid=github_onlyfans-scraper)

Here is the sample output of this actor:

```json
{
	"view": "f",
	"avatar": "https://public.onlyfans.com/files/a/as/asi/asia5qn6votatqej9ewpzlha7mbg5mfu1674166354/82054335/avatar.jpg",
	"avatarThumbs": {
		"c50": "https://public.onlyfans.com/files/thumbs/c50/a/as/asi/asia5qn6votatqej9ewpzlha7mbg5mfu1674166354/82054335/avatar.jpg",
		"c144": "https://public.onlyfans.com/files/thumbs/c144/a/as/asi/asia5qn6votatqej9ewpzlha7mbg5mfu1674166354/82054335/avatar.jpg"
	},
	"header": "https://public.onlyfans.com/files/u/uo/uob/uob3flykmzbhnbgcqm7pppsxwdpvde9l1674168366/82054335/header.jpg",
	"headerSize": {
		"width": 600,
		"height": 200
	},
	"headerThumbs": {
		"w480": "https://public.onlyfans.com/files/thumbs/w480/u/uo/uob/uob3flykmzbhnbgcqm7pppsxwdpvde9l1674168366/82054335/header.jpg",
		"w760": "https://public.onlyfans.com/files/thumbs/w760/u/uo/uob/uob3flykmzbhnbgcqm7pppsxwdpvde9l1674168366/82054335/header.jpg"
	},
	"id": 82054335,
	"name": "☕️Coffee and Cleavage",
	"username": "coffeeandcleavage",
	"canLookStory": false,
	"canCommentStory": false,
	"hasNotViewedStory": false,
	"isVerified": true,
	"canPayInternal": false,
	"hasScheduledStream": false,
	"hasStream": false,
	"hasStories": false,
	"tipsEnabled": false,
	"tipsTextEnabled": true,
	"tipsMin": 5,
	"tipsMinInternal": 1,
	"tipsMax": 200,
	"canEarn": true,
	"canAddSubscriber": true,
	"subscribePrice": 0,
	"unprofitable": true,
	"isMuted": false,
	"isRestricted": false,
	"canRestrict": true,
	"subscribedBy": false,
	"subscribedByExpire": null,
	"subscribedByExpireDate": null,
	"subscribedByAutoprolong": null,
	"subscribedIsExpiredNow": null,
	"currentSubscribePrice": null,
	"subscribedOn": false,
	"subscribedOnExpiredNow": null,
	"subscribedOnDuration": null,
	"joinDate": "2020-10-26T00:00:00+00:00",
	"isReferrerAllowed": true,
	"about": "☕️Podcast hosted by @misslynniemarie &amp; @shantalmonique 💞<br />\n🎙Episode released every Wednesday 2pmPST!!",
	"rawAbout": "☕️Podcast hosted by @misslynniemarie & @shantalmonique 💞\n🎙Episode released every Wednesday 2pmPST!!",
	"website": "https://www.Coffeeandcleavage.com",
	"wishlist": null,
	"location": null,
	"postsCount": 301,
	"archivedPostsCount": 1,
	"privateArchivedPostsCount": 0,
	"photosCount": 145,
	"videosCount": 165,
	"audiosCount": 0,
	"mediasCount": 310,
	"lastSeen": "2023-06-14T15:07:05+00:00",
	"favoritesCount": 221,
	"favoritedCount": 120053,
	"showPostsInFeed": false,
	"canReceiveChatMessage": false,
	"isPerformer": true,
	"isRealPerformer": true,
	"isSpotifyConnected": false,
	"subscribersCount": 732645,
	"hasPinnedPosts": true,
	"hasLabels": true,
	"canChat": true,
	"callPrice": 0,
	"isPrivateRestriction": false,
	"showSubscribersCount": true,
	"showMediaCount": true,
	"subscribedByData": null,
	"subscribedOnData": null,
	"canPromotion": true,
	"canCreatePromotion": false,
	"canCreateTrial": false,
	"isAdultContent": false,
	"canTrialSend": false,
	"hadEnoughLastPhotos": false,
	"hasLinks": false,
	"referalBonusSummForReferer": 0,
	"finishedStreamsCount": 15,
	"shouldShowFinishedStreams": true,
	"hasSavedStreams": true,
	"firstPublishedPostDate": "2020-11-04T00:00:00+00:00",
	"isSpringConnected": false,
	"isFriend": false,
	"isBlocked": false,
	"canReport": false,
	"instagramUrl": "https://instagram.com/coffeeandcleavage",
	"youtubeUrl": "https://youtube.com/coffeeandcleavage",
	"facebookUrl": "https://facebook.com/coffeeandclevage",
	"twitterUrl": "https://twitter.com/coffeecleavage"
}
```

## OnlyFans Profile JSON Data Documentation

This documentation provides a detailed description of the fields and structures in the provided JSON data representing an OnlyFans profile.

## Fields

2. `avatar`: (string) - This is the URL to the profile avatar or profile picture.

3. `avatarThumbs`: (object) - Contains URLs to thumbnail versions of the profile picture.
    - `c50`: URL to a thumbnail with specific dimensions.
    - `c144`: URL to another thumbnail with specific dimensions.

4. `header`: (string) - The URL to the profile's header image.

5. `headerSize`: (object) - Contains dimensions of the header image.
    - `width`: The width of the header image.
    - `height`: The height of the header image.

6. `headerThumbs`: (object) - Contains URLs to thumbnail versions of the header image.
    - `w480`: URL to a thumbnail with specific width.
    - `w760`: URL to another thumbnail with specific width.

7. `id`: (integer) - The unique identifier of the profile.

8. `name`: (string) - The display name of the profile.

9. `username`: (string) - The unique username of the profile.

10. `canLookStory`: (boolean) - Indicates if a user is permitted to view the profile's story.

11. `canCommentStory`: (boolean) - Indicates if a user can comment on the profile's story.

12. `hasNotViewedStory`: (boolean) - Indicates if the user has not viewed the profile's story.

13. `isVerified`: (boolean) - Indicates if the profile is verified.

14. `canPayInternal`: (boolean) - Not clear from the provided data, may indicate internal payment capabilities.

15. `hasScheduledStream`: (boolean) - Indicates if the profile has a scheduled live stream.

16. `hasStream`: (boolean) - Indicates if the profile is currently streaming.

17. `hasStories`: (boolean) - Indicates if the profile has any stories.

18. `tipsEnabled`: (boolean) - Indicates if tipping is enabled for the profile.

19. `tipsTextEnabled`: (boolean) - Indicates if text is enabled in tips.

20. `tipsMin`: (integer) - The minimum amount that can be tipped.

21. `tipsMinInternal`: (integer) - The minimum internal amount that can be tipped.

22. `tipsMax`: (integer) - The maximum amount that can be tipped.

23. `canEarn`: (boolean) - Indicates if the profile can earn money.

24. `canAddSubscriber`: (boolean) - Indicates if the profile can add subscribers.

25. `subscribePrice`: (integer) - The subscription price for the profile.

26. `unprofitable`: (boolean) - Indicates if the profile is unprofitable.

27. `isMuted`: (boolean) - Indicates if the profile is muted.

28. `isRestricted`: (boolean) - Indicates if the profile is restricted.

29. `canRestrict`: (boolean) - Indicates if the profile can be restricted.

30. `subscribedBy`: (boolean) - Indicates if the user is subscribed to the profile.

31. `subscribedByExpire`: (null) - Indicates the expiry of the user's subscription, null if not applicable.

32. `subscribedByExpireDate`: (null) - The date when the user's subscription expires, null if not applicable.

33. `subscribedByAutoprolong`: (null) - Not clear from the provided data, might indicate if the user's subscription will automatically renew.

34. `subscribedIsExpiredNow`: (null) - Indicates if the user's subscription has expired, null if not applicable.

35. `currentSubscribePrice`: (null) - The current subscription price, null if not applicable.

36. `subscribedOn`: (boolean) - Indicates if the user has subscribed on the platform.

37. `subscribedOnExpiredNow`: (null) - Indicates if the user's subscription on the platform has expired, null if not applicable.

38. `subscribedOnDuration`: (null) - The duration of the user's subscription on the platform, null if not applicable.

39. `joinDate`: (string) - The date the profile was created.

40. `isReferrerAllowed`: (boolean) - Indicates if referrals are allowed.

41. `about`: (string) - The profile's about section with HTML elements.

42. `rawAbout`: (string) - The profile's about section in raw text.

43. `website`: (string) - The profile's website.

44. `wishlist`: (null) - The profile's wishlist, null if not applicable.

45. `location`: (null) - The profile's location, null if not disclosed.

46. `postsCount`: (integer) - The total number of posts by the profile.

47. `archivedPostsCount`: (integer) - The total number of archived posts by the profile.

48. `privateArchivedPostsCount`: (integer) - The total number of private archived posts by the profile.

49. `photosCount`: (integer) - The total number of photos posted by the profile.

50. `videosCount`: (integer) - The total number of videos posted by the profile.

51. `audiosCount`: (integer) - The total number of audio files posted by the profile.

52. `mediasCount`: (integer) - The total number of media files (photos, videos, audio) posted by the profile.

53. `lastSeen`: (string) - The date and time the profile was last seen online.

54. `favoritesCount`: (integer) - The total number of favorites of the profile.

55. `favoritedCount`: (integer) - The total number of times the profile has been favorited by others.

56. `showPostsInFeed`: (boolean) - Indicates if posts from this profile show in feeds.

57. `canReceiveChatMessage`: (boolean) - Indicates if the profile can receive chat messages.

58. `isPerformer`: (boolean) - Indicates if the profile is a performer.

59. `isRealPerformer`: (boolean) - Indicates if the profile is a real performer.

60. `isSpotifyConnected`: (boolean) - Indicates if Spotify is connected to the profile.

61. `subscribersCount`: (integer) - The total number of subscribers of the profile.

62. `hasPinnedPosts`: (boolean) - Indicates if the profile has any pinned posts.

63. `hasLabels`: (boolean) - Indicates if the profile has any labels.

64. `canChat`: (boolean) - Indicates if users can chat with the profile.

65. `callPrice`: (integer) - The price for a call with the profile.

66. `isPrivateRestriction`: (boolean) - Indicates if there are any private restrictions on the profile.

67. `showSubscribersCount`: (boolean) - Indicates if the number of subscribers is displayed.

68. `showMediaCount`: (boolean) - Indicates if the count of media is displayed.

69. `subscribedBy

Data`: (null) - Contains data about the user's subscription, null if not applicable.

70. `subscribedOnData`: (null) - Contains data about the user's on-platform subscription, null if not applicable.

71. `canPromotion`: (boolean) - Indicates if promotions can be created for the profile.

72. `canCreatePromotion`: (boolean) - Indicates if the profile can create promotions.

73. `canCreateTrial`: (boolean) - Indicates if the profile can create trial subscriptions.

74. `isAdultContent`: (boolean) - Indicates if the profile contains adult content.

75. `canTrialSend`: (boolean) - Indicates if trial subscriptions can be sent.

77. `hasLinks`: (boolean) - Indicates if the profile has links to external sites.

78. `referalBonusSummForReferer`: (integer) - The referral bonus sum for the referrer.

79. `finishedStreamsCount`: (integer) - The total number of finished live streams by the profile.

80. `shouldShowFinishedStreams`: (boolean) - Indicates if finished streams should be shown.

81. `hasSavedStreams`: (boolean) - Indicates if the profile has any saved streams.

82. `firstPublishedPostDate`: (string) - The date of the first post published by the profile.

83. `isSpringConnected`: (boolean) - Indicates if Spring (formerly known as Teespring, a platform for custom merchandise) is connected to the profile.

84. `isFriend`: (boolean) - Indicates if the user is a friend of the profile.

85. `isBlocked`: (boolean) - Indicates if the profile is blocked.

86. `canReport`: (boolean) - Indicates if the profile can be reported.

87. `instagramUrl`: (string) - The profile's Instagram URL.

88. `youtubeUrl`: (string) - The profile's YouTube URL.

89. `facebookUrl`: (string) - The profile's Facebook URL.

90. `twitterUrl`: (string) - The profile's Twitter URL.

