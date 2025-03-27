# Change log

## [1.7.0] - 2025-03-27

### Added

- `403` response for the PUT operation of path `/api/v1/user/preferences/{name}`
- `409` response for the POST operation of path `/api/v1/groups/{id}/assign`
- `locked` property in the `userPreference` model

## [1.6.0] - 2024-11-08

### Added

- New `otpauth` query parameter for the GET operation of path `/api/v1/twofaccounts/export` to force data export as otpauth URIs instead of the 2FAuth json format.

## [1.5.0] - 2024-09-27

### Added

- New `group_id` property for POST and PUT operations of the `/api/v1/twofaccounts` path

## [1.4.0] - 2024-05-14

### Added

- `/api/v1/users/{id}/authentications` GET path

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
