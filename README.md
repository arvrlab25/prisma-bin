# prisma-bin

https://binaries.prisma.sh/all_commits/{COMMIT_ID}/{PLATFORM}/{ENGINE_NAME}.gz

where
COMMIT_ID: Full commit hash from https://github.com/prisma/prisma-engines. You can check the tags page for specific commit which relates to the release you want: https://github.com/prisma/prisma-engines/tags
PLATFORM: Platform of your choice. Full list here: https://www.prisma.io/docs/reference/api-reference/prisma-schema-reference#binarytargets-options
ENGINE_NAME: Engine you want to download. One of libquery_engine.so.node, query-engine, migration-engine, introspection-engine and prisma-fmt.

Example:
https://binaries.prisma.sh/all_commits/694eea289a8462c80264df36757e4fdc129b1b32/debian-openssl-3.0.x/libquery_engine.so.node.gz