> [!NOTE]
> some of the element names are already an option in settings

> [!TIP]
> some ui elements like buttons can be specifically hidden based on the text
>
> example is `button$Undo` where it hides buttons containing the english text "Undo"

# general element paths

* `avatar`
* `button`
* `button_inner`
* `card`
* `chip`
* `thumbnail`

# specific element paths

| element name                               | about                                                                                                                                      
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------
| `author_badge`                             |                                                                                                                                            
| `avatar_with_ring`                         |
| `basic_content`                            |
| `bottom_sheet_footer`                      |
| `bottom_sheet_header`                      |
| `bottom_sheet_list_option`                 |
| `bottom_sheet_list_option_temporary_clone` | bottom sheet flyout menu item?                                                                                                             
| `cell_divider`                             |
| `chip_bar`                                 |
| `comment_header`                           | "Comments are paused" for example                                                                                                          
| `comment_thread`                           | the regular comments in the comment section                                                                                                
| `compact_channel`                          | the channel bar in the watch page - 20.13.41, but also the same element from search results - channel box to subscribe or view the channel
| `compact_video`                            | videos in the channel page at "videos"
| `decorated_avatar`                         |
| `default_pinned_comment_thread`            | the pinned comment in the comment section
| `divider`                                  |
| `engagement_dislike_button`                | dislike button in the comment card
| `engagement_like_button`                   | like button in the comment card
| `flexible_actions`                         |
| `image_banner`                             | the image banner in a channel's page
| `images_post_slim`                         |
| `images_post_root_slim`                    |
| `live_ring`                                |
| `more_drawer`                              | the explore button in the home page filter bar
| `page_header`                              | the header in a channel's page
| `player_overlay_video_heading`             | the video title overlay in fullscreen video player
| `post_animated_like_button_with_url`       |
| `post_author`                              |
| `post_comment_button`                      | the button in a community post to open the comment section
| `post_comments_carousel`                   |
| `post_engagement_toolbar_slim`             |
| `post_header`                              |
| `post_image_attachment_slim`               |
| `post_image_lightbox`                      |
| `post_like_dislike`                        | community post's like and dislike button grouped together in one container
| `post_like_dislike_slim`                   |
| `post_menu`                                |
| `post_share_button`                        |
| `post_text`                                | the caption / text in a community post
| `post_time_metadata`                       | the publish time in a community post
| `status_dot`                               | the blue dot in each of the subscribed channels in subscriptions page
| `styled_product_carousel_item`             |
| `subscriptions_channel_bar`                |
| `subscriptions_channel_bar_channel`        |
| `subscriptioms_channel_bar_horizontal`     |
| `subscriptions_chip_bar`                   |
| `thumbnail_badge`                          | notably the video's length time
| `video_lockup`                             | a long-form video item
| `video_lockup_attachments`                 |
| `video_lockup_metadata`                    |
| `video_lockup_with_attachment`             |
| `view_replies_button`                      | in the comment section

# general element paths with ampersand

| element name                  | about                                                                                                                                      
|-------------------------------|--------------
| `avatar&comment`              | the profile pictures in the comments at the comnent section

# element paths with buffer strings

| element name                                           | about                                                                                                                                      
|--------------------------------------------------------|--------------------------------------------
| `bottom_sheet_list_option_temporary_clone$Unsubscribe` | the unsubscribe option in the flyout menu, from the watch page for example
| `button$Ignore limit for today`                        | the button from shorts limit popup
| `button$Get Premium`                                   | the "Get Premium" in You page
| `card$basic_content`                                   | automatically hides the card "We won't recommend videos from this channel" and similar variants
| `compact_video$Members only`                           | targets "Members only" videos in a channel page
| `video_lockup$relatedH`                                | targets related videos under the player in watch page
