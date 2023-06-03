# TODO:

### global:
1. Set new name (e.g. "GT Cloud Explorer") and ico (gen via AI)
2. make all repo private or add LICENSE
3. Remove TSP from CP repo (not TSP repo)

### server:
1. b64: change encoding (or push query via text/data parameter)
2. /get?title=... must return response with err (not found) or url to file downloading (download via flutter_download_manager)
3. remove /shutdown as useless
4. on path /get request return list of files from path as items (title = filename)
5. add logs to file or/and stream (stdout/stdin/stderr)
6. move file data (data.json) to {home}/Docs/CP dir

### process_utils:
1. Just create adapter of some default lib (if exists) OR add new funcs (e.g. is_running_by_name(); pid-like funcs)
2. Add README.md to package

### client:
1. Rework file dirs (Grid-like view)
2. Fix/change Hive (may be new Class Settings, loaded on init server page)
3. Add themes.
4. Add support for urls.

### TSP:
1. Remove this trash.