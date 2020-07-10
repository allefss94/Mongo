# mongod
2020-07-09T22:48:46.888-0300 I  CONTROL  [main] Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'
2020-07-09T22:48:47.232-0300 W  ASIO     [main] No TransportLayer configured during NetworkInterface startup
2020-07-09T22:48:47.233-0300 I  CONTROL  [initandlisten] MongoDB starting : pid=2264 port=27017 dbpath=C:\data\db\ 64-bit host=DESKTOP-RGSIVEA
2020-07-09T22:48:47.233-0300 I  CONTROL  [initandlisten] targetMinOS: Windows 7/Windows Server 2008 R2
2020-07-09T22:48:47.233-0300 I  CONTROL  [initandlisten] db version v4.2.8
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten] git version: 43d25964249164d76d5e04dd6cf38f6111e21f5f
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten] allocator: tcmalloc
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten] modules: none
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten] build environment:
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten]     distmod: 2012plus
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten]     distarch: x86_64
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten]     target_arch: x86_64
2020-07-09T22:48:47.234-0300 I  CONTROL  [initandlisten] options: {}
2020-07-09T22:48:47.235-0300 I  STORAGE  [initandlisten] wiredtiger_open config: create,cache_size=4577M,cache_overflow=(file_max=0M),session_max=33000,eviction=(threads_min=4,threads_max=4),config_base=false,statistics=(fast),log=(enabled=true,archive=true,path=journal,compressor=snappy),file_manager=(close_idle_time=100000,close_scan_interval=10,close_handle_minimum=250),statistics_log=(wait=0),verbose=[recovery_progress,checkpoint_progress],
2020-07-09T22:48:47.513-0300 I  STORAGE  [initandlisten] WiredTiger message [1594345727:513293][2264:140719673922800], txn-recover: Set global recovery timestamp: (0, 0)
2020-07-09T22:48:47.687-0300 I  RECOVERY [initandlisten] WiredTiger recoveryTimestamp. Ts: Timestamp(0, 0)
2020-07-09T22:48:48.075-0300 I  STORAGE  [initandlisten] Timestamp monitor starting
2020-07-09T22:48:48.233-0300 I  CONTROL  [initandlisten]
2020-07-09T22:48:48.233-0300 I  CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2020-07-09T22:48:48.233-0300 I  CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2020-07-09T22:48:48.234-0300 I  CONTROL  [initandlisten]
2020-07-09T22:48:48.234-0300 I  CONTROL  [initandlisten] ** WARNING: This server is bound to localhost.
2020-07-09T22:48:48.235-0300 I  CONTROL  [initandlisten] **          Remote systems will be unable to connect to this server.
2020-07-09T22:48:48.235-0300 I  CONTROL  [initandlisten] **          Start the server with --bind_ip <address> to specify which IP
2020-07-09T22:48:48.235-0300 I  CONTROL  [initandlisten] **          addresses it should serve responses from, or with --bind_ip_all to
2020-07-09T22:48:48.235-0300 I  CONTROL  [initandlisten] **          bind to all interfaces. If this behavior is desired, start the
2020-07-09T22:48:48.236-0300 I  CONTROL  [initandlisten] **          server with --bind_ip 127.0.0.1 to disable this warning.
2020-07-09T22:48:48.236-0300 I  CONTROL  [initandlisten]
2020-07-09T22:48:48.237-0300 I  STORAGE  [initandlisten] createCollection: admin.system.version with provided UUID: 11044a5a-0738-4a23-80ad-84ac76efa238 and options: { uuid: UUID("11044a5a-0738-4a23-80ad-84ac76efa238") }
2020-07-09T22:48:48.353-0300 I  INDEX    [initandlisten] index build: done building index _id_ on ns admin.system.version
2020-07-09T22:48:48.354-0300 I  SHARDING [initandlisten] Marking collection admin.system.version as collection version: <unsharded>
2020-07-09T22:48:48.355-0300 I  COMMAND  [initandlisten] setting featureCompatibilityVersion to 4.2
2020-07-09T22:48:48.356-0300 I  SHARDING [initandlisten] Marking collection local.system.replset as collection version: <unsharded>
2020-07-09T22:48:48.356-0300 I  STORAGE  [initandlisten] Flow Control is enabled on this deployment.
2020-07-09T22:48:48.357-0300 I  SHARDING [initandlisten] Marking collection admin.system.roles as collection version: <unsharded>
2020-07-09T22:48:48.357-0300 I  STORAGE  [initandlisten] createCollection: local.startup_log with generated UUID: 5733204e-b40f-45d0-bd35-0178b23f9885 and options: { capped: true, size: 10485760 }
2020-07-09T22:48:48.485-0300 I  INDEX    [initandlisten] index build: done building index _id_ on ns local.startup_log
2020-07-09T22:48:48.485-0300 I  SHARDING [initandlisten] Marking collection local.startup_log as collection version: <unsharded>
2020-07-09T22:48:48.737-0300 W  FTDC     [initandlisten] Failed to initialize Performance Counters for FTDC: WindowsPdhError: PdhExpandCounterPathW failed with 'O objeto especificado não foi encontrado no computador.' for counter '\Memory\Available Bytes'
2020-07-09T22:48:48.737-0300 I  FTDC     [initandlisten] Initializing full-time diagnostic data capture with directory 'C:/data/db/diagnostic.data'
2020-07-09T22:48:48.739-0300 I  SHARDING [LogicalSessionCacheRefresh] Marking collection config.system.sessions as collection version: <unsharded>
2020-07-09T22:48:48.740-0300 I  CONTROL  [LogicalSessionCacheReap] Sessions collection is not set up; waiting until next sessions reap interval: config.system.sessions does not exist
2020-07-09T22:48:48.740-0300 I  NETWORK  [listener] Listening on 127.0.0.1
2020-07-09T22:48:48.740-0300 I  STORAGE  [LogicalSessionCacheRefresh] createCollection: config.system.sessions with provided UUID: d419a1dc-286b-4e7d-acb0-f31e73a0ad71 and options: { uuid: UUID("d419a1dc-286b-4e7d-acb0-f31e73a0ad71") }
2020-07-09T22:48:48.740-0300 I  NETWORK  [listener] waiting for connections on port 27017
2020-07-09T22:48:48.877-0300 I  INDEX    [LogicalSessionCacheRefresh] index build: done building index _id_ on ns config.system.sessions
2020-07-09T22:48:49.004-0300 I  SHARDING [ftdc] Marking collection local.oplog.rs as collection version: <unsharded>
2020-07-09T22:48:49.069-0300 I  INDEX    [LogicalSessionCacheRefresh] index build: starting on config.system.sessions properties: { v: 2, key: { lastUse: 1 }, name: "lsidTTLIndex", ns: "config.system.sessions", expireAfterSeconds: 1800 } using method: Hybrid
2020-07-09T22:48:49.069-0300 I  INDEX    [LogicalSessionCacheRefresh] build may temporarily use up to 200 megabytes of RAM
2020-07-09T22:48:49.070-0300 I  INDEX    [LogicalSessionCacheRefresh] index build: collection scan done. scanned 0 total records in 0 seconds
2020-07-09T22:48:49.074-0300 I  INDEX    [LogicalSessionCacheRefresh] index build: inserted 0 keys from external sorter into index in 0 seconds
2020-07-09T22:48:49.135-0300 I  INDEX    [LogicalSessionCacheRefresh] index build: done building index lsidTTLIndex on ns config.system.sessions
2020-07-09T22:48:49.248-0300 I  COMMAND  [LogicalSessionCacheRefresh] command config.system.sessions command: createIndexes { createIndexes: "system.sessions", indexes: [ { key: { lastUse: 1 }, name: "lsidTTLIndex", expireAfterSeconds: 1800 } ], $db: "config" } numYields:0 reslen:114 locks:{ ParallelBatchWriterMode: { acquireCount: { r: 2 } }, ReplicationStateTransition: { acquireCount: { w: 3 } }, Global: { acquireCount: { r: 1, w: 2 } }, Database: { acquireCount: { r: 1, w: 2, W: 1 } }, Collection: { acquireCount: { r: 4, w: 1, R: 1, W: 2 } }, Mutex: { acquireCount: { r: 3 } } } flowControl:{ acquireCount: 1, timeAcquiringMicros: 1 } storage:{} protocol:op_msg 507ms
  
  
  #mongo
  
  PS C:\Users\55949> mongo
MongoDB shell version v4.2.8
connecting to: mongodb://127.0.0.1:27017/?compressors=disabled&gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("52587fb0-91ae-4780-a5c2-b35882752426") }
MongoDB server version: 4.2.8
Server has startup warnings:
2020-07-09T22:48:42.979-0300 I  CONTROL  [initandlisten]
2020-07-09T22:48:42.979-0300 I  CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2020-07-09T22:48:42.979-0300 I  CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2020-07-09T22:48:42.979-0300 I  CONTROL  [initandlisten]
---
Enable MongoDB's free cloud-based monitoring service, which will then receive and display
metrics about your deployment (disk utilization, CPU, operation statistics, etc).

The monitoring data will be available on a MongoDB website with a unique URL accessible to you
and anyone you share the URL with. MongoDB may use this information to make product
improvements and to suggest MongoDB products and deployment options to you.

To enable free monitoring, run the following command: db.enableFreeMonitoring()
To permanently disable this reminder, run the following command: db.disableFreeMonitoring()
