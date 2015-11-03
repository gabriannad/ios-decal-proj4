## Journy

## Authors
* Gabrianna Dumaguin

## Purpose
Journy is social media app that lets you make more meaningful stories
("journies") out of your photos and other content you post online. A
single journy tells a single, more meaningful story, whether it's your
progress on learning how to box or your trip to South America.

## Features
* Create a Journy
* Add a post to your Journy
  * Upload new content
  * Import Facebook photos
  * Import content from other social media sites (if time permits)
* Follow other people's Journies
* View a Journy
* View a single post in a Journy

## Control Flow
* User first presented with a feed of posts from Journies they follow
  * From the feed, user can tap to view the full post or view the full Journy
* User can manage his/her social media accounts that are linked to his/her
  Journy account
* From any screen, user can create a new Journy or create a new post to
  add to an existing Journy
  * User can choose to import content from other social media accounts
    or directly add new content directly from app
* User can view his/her own profile

## Implementation
### Model
* Journy.swift
* Post.swift
* User.swift

## View
* FeedTableView
* JournyTableView
* SinglePostView
* AddNewPostView
* ImportPhotoCollectionView
* ProfileView

## Controllers
* FeedTableViewController
* JournyTableViewController
* SinglePostViewController
* AddNewPostViewController
* ImportPhotoCollectionViewController
* ProfileViewController
