# Change log

## [1.3.0] - 2024-03-15

### Added

- `/api/v1/users` paths
- `oauth_provider` property to the response body of `/api/v1/user` GET path

## [1.2.0] - 2023-12-22

### Added

- `/api/v1/user` GET path
- `ids` and `withOtp` query parameters to the `/api/v1/twofaccounts` GET path

## [1.1.0] - 2023-03-23

### Added

- `/api/v1/user/preferences` GET path
- `/api/v1/user/preferences/{name}` GET & PUT paths
- `/api/v1/twofaccounts/export` GET path
- `/api/v1/twofaccounts/migration` POST path
- Error 500 to file upload endpoints responses

### Changed

- Identify Settings endpoints as Admin only endpoints with tags
- Request body for Icon & QRcode POST are now binary format
- Update QR code paths descriptions

### Deprecated

- `/user/name` GET path

### Removed

- 404 response from `/api/v1/twofaccounts/otp` POST path

## [1.0.0] - 2022-04-13

Initial release
