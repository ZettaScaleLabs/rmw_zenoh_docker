# `rmw_zenoh` Docker image

This is useful for platforms where installing ROS2 is too much of a pain (_cough_ macOS _cough cough_).

## Usage

```bash
docker buildx build --tag rmw-zenoh-fix-issue-1274 --build-arg RMW_ZENOH_BRANCH="fix-issue-1274" --progress=plain .
```
