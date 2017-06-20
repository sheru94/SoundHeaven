# API Endpoints

## HTML API

### Root

- `GET /` - loads React web app

## JSON API

### Users

- `POST /api/users`
- `PATCH /api/users`

### Session

- `POST /api/session`
- `DELETE /api/session`

### Tracks
- `GET /api/tracks`
  returns all tracks
- `POST /api/tracks`
  required data: Title, Song_file,
- `GET /api/tracks/:id`
  required params: track_id
- `PATCH /api/tracks/:id`
  required params: track_id
- `DELETE /api/tracks/:id`
  required params: track_id


### Comments
- `GET /api/tracks/track_id/comments`
- `POST /api/tracks/track_id/comments`
  required data: body, track_id
