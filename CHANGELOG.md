# 1.0.0
- Added `client` and `backend` fields in addition to `client:port`, `backend:port` fields that can be used to group by IPs as opposed to IP:port pairs.
- Added filtering by date using `--start` and `--end` arguments.
- Added library mode that allows log analyzer to be used in other code using `require()`.

# 0.3.0
- Re-writtent to be much more performant than previous versions. Almost never goes out of memory anymore.

# 0.2.1
- Added support for querying ```user_agent``` attribute
