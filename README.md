# api-instagram

Api Follow : https://www.instagram.com/web/friendships/{id}/follow/

Api Unfollow : https://www.instagram.com/web/friendships/{id}/unfollow/

Api hearthPost : https://www.instagram.com/web/likes/{idpost}/like/

Api UnhearthPost : https://www.instagram.com/web/likes/{idpost}/unlike/

Api Comment : https://www.instagram.com/web/comments/{idpost}/add/ -- data = "comment_text=" + content + "&replied_to_comment_id="

Api Remove Comment : https://www.instagram.com/web/comments/{idpost}/delete/{idcomment}/

Change Avt : https://www.instagram.com/accounts/web_change_profile_picture/ -- files = {'profile_pic': open(path, 'rb')}

changeProfie : https://www.instagram.com/accounts/edit/?__d=dis -- "data = urllib.parse.urlencode({ "first_name": name, "chaining_enabled": chaining_enabled, "email": email, "phone_number": sdt, "biography": bio, "external_url": pepWebsite, "username": pepName })"
