# Graph Report - .  (2026-07-09)

## Corpus Check
- Corpus is ~47,239 words - fits in a single context window. You may not need a graph.

## Summary
- 581 nodes · 1099 edges · 45 communities (27 shown, 18 thin omitted)
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 50 edges (avg confidence: 0.73)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Response Fronting Support|Response Fronting Support]]
- [[_COMMUNITY_Ip Lan Google|Ip Lan Google]]
- [[_COMMUNITY_H2 Transport H2transport|H2 Transport H2transport]]
- [[_COMMUNITY_Cert Installer Install|Cert Installer Install]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Support Socks5|Support Socks5]]
- [[_COMMUNITY_Server Proxyserver Direct|Server Proxyserver Direct]]
- [[_COMMUNITY_Server Proxyserver Support|Server Proxyserver Support]]
- [[_COMMUNITY_Server Proxyserver Do|Server Proxyserver Do]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Vps Exit Node|Vps Exit Node]]
- [[_COMMUNITY_Logging Utils Prettyformatter|Logging Utils Prettyformatter]]
- [[_COMMUNITY_Adblock Cache Parsehoststexttests|Adblock Cache Parsehoststexttests]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Setup Configure Config|Setup Configure Config]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Exit Node Architecture|Exit Node Architecture]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Support Proxysupporttests Server|Support Proxysupporttests Server]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Support Responsecache Responsecacheparsettltests|Support Responsecache Responsecacheparsettltests]]
- [[_COMMUNITY_Readme Architecture Configuration|Readme Architecture Configuration]]
- [[_COMMUNITY_Cloudflare Worker Decodebase64tobytes|Cloudflare Worker Decodebase64tobytes]]
- [[_COMMUNITY_Setup Vps Exit|Setup Vps Exit]]
- [[_COMMUNITY_Domain Fronter Domainfronter|Domain Fronter Domainfronter]]
- [[_COMMUNITY_Deno Deploy Decodebase64tobytes|Deno Deploy Decodebase64tobytes]]
- [[_COMMUNITY_Codec Codectests And|Codec Codectests And]]
- [[_COMMUNITY_Start Find Python|Start Find Python]]
- [[_COMMUNITY_Init|Init]]
- [[_COMMUNITY_Graphify  Agents|Graphify  Agents]]
- [[_COMMUNITY_Graphify  Agents|Graphify  Agents]]
- [[_COMMUNITY_Funding|Funding ]]
- [[_COMMUNITY_Ci  Workflow|Ci  Workflow]]
- [[_COMMUNITY_Docker Release|Docker Release ]]
- [[_COMMUNITY_Release  Workflow|Release  Workflow]]
- [[_COMMUNITY_Docker Compose Service|Docker Compose Service]]
- [[_COMMUNITY_Docker Setup|Docker Setup]]
- [[_COMMUNITY_Docker|Docker]]
- [[_COMMUNITY_Getting Started|Getting Started]]
- [[_COMMUNITY_Requirements Brotli|Requirements Brotli]]
- [[_COMMUNITY_Requirements Cryptography|Requirements Cryptography]]
- [[_COMMUNITY_Requirements H2|Requirements H2]]
- [[_COMMUNITY_Requirements Zstandard|Requirements Zstandard]]

## God Nodes (most connected - your core abstractions)
1. `DomainFronter` - 95 edges
2. `ProxyServer` - 44 edges
3. `H2Transport` - 22 edges
4. `main()` - 12 edges
5. `_run()` - 12 edges
6. `ScriptDeploymentError` - 12 edges
7. `main()` - 11 edges
8. `ResponseCache` - 11 edges
9. `MITMCertManager` - 10 edges
10. `classify_relay_envelope()` - 10 edges

## Surprising Connections (you probably didn't know these)
- `MasterHttpRelayVPN (FA)` --semantically_similar_to--> `MasterHttpRelayVPN`  [INFERRED] [semantically similar]
  README_FA.md → README.md
- `main()` --calls--> `install_ca()`  [INFERRED]
  main.py → src/core/cert_installer.py
- `main()` --calls--> `is_ca_trusted()`  [INFERRED]
  main.py → src/core/cert_installer.py
- `main()` --calls--> `uninstall_ca()`  [INFERRED]
  main.py → src/core/cert_installer.py
- `main()` --calls--> `print_banner()`  [INFERRED]
  main.py → src/core/logging_utils.py

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Documentation Guides** — docs_architecture_architecture, docs_configuration_configuration, docs_docker_docker_setup, docs_getting_started_getting_started [INFERRED 0.85]
- **MasterHttpRelayVPN Traffic Path** — docs_fa_architecture_md_local_proxy, docs_fa_architecture_md_apps_script_relay, docs_fa_architecture_md_exit_node [EXTRACTED 1.00]

## Communities (45 total, 18 thin omitted)

### Community 0 - "Response Fronting Support"
Cohesion: 0.05
Nodes (53): Apps Script relay engine.  Domain fronting via Google Apps Script: POST JSON t, Chain: Apps Script → edge relay (exit node) → Destination.          Traffic pa, Relay with parallel range acceleration for large downloads.          Strategy:, Stream a large range-capable download to the client incrementally.          Re, Rewrite a 206 Partial Content response to 200 OK.          Used when we probed, Build the JSON relay payload dict., # IMPORTANT: always use the filtered dict — never fall back to, Parse a batch response body into individual results. (+45 more)

### Community 1 - "Ip Lan Google"
Cohesion: 0.06
Nodes (33): main(), _make_exception_handler(), parse_args(), Return an asyncio exception handler that silences Windows WinError 10054     no, _run(), Semaphore, decode(), Content-Encoding decoders: gzip (stdlib), brotli (optional), zstd (optional). (+25 more)

### Community 2 - "H2 Transport H2transport"
Cohesion: 0.09
Nodes (18): H2Transport, HTTP/2 multiplexed transport for domain-fronted connections.  One TLS connecti, Connect if not already connected., Establish the HTTP/2 connection with optimized socket settings., Close current connection and re-establish, with backoff.          Multiple con, Send an HTTP/2 request and return (status, headers, body).          Thread-saf, Send one HTTP/2 request on a new stream, wait for response., Start the connection-level inflight pinger if not already running.          ON (+10 more)

### Community 3 - "Cert Installer Install"
Cohesion: 0.11
Nodes (33): CompletedProcess, _cert_thumbprint(), _detect_linux_distro(), _has_cmd(), install_ca(), _install_firefox(), _install_linux(), _install_macos() (+25 more)

### Community 4 - "Domain Fronter Domainfronter"
Cohesion: 0.12
Nodes (8): DomainFronter, Return True if this URL should be routed through the exit node., Relay an HTTP request through Apps Script.          Features:           - Pre, Dedup concurrent requests for the same URL (no Range header).          Uses `_, Strip field-3 (quality-track selection) entries from a SABR         segment-fet, Return a stable routing key for a URL or host string., HostStat, Per-host traffic accounting — useful for profiling slow / heavy sites.

### Community 5 - "Domain Fronter Domainfronter"
Cohesion: 0.12
Nodes (15): _mask_sid(), Build the /macros/s/<sid>/exec path for a specific script ID., Headers for Apps Script relay calls (control-plane, not target origin)., Pre-warm Apps Script via /exec., Fire the same relay against N distinct script IDs in parallel.          Return, Execute a relay through HTTP/2 multiplexing.          Picks a connection from, Execute an H2 relay pinned to a specific Apps Script deployment.          Used, Execute a single relay POST → redirect → parse. (+7 more)

### Community 6 - "Support Socks5"
Cohesion: 0.12
Nodes (14): Logger, Central location for tunable constants used across the project.  Values here a, Local HTTP proxy server.  Intercepts the user's browser traffic and forwards e, host_matches_rules(), load_host_rules(), log_response_summary(), Proxy helper utilities: header parsing, host rule matching, response caching, C, Accept a list of host strings; return (exact_set, suffix_tuple). (+6 more)

### Community 7 - "Server Proxyserver Direct"
Cohesion: 0.13
Nodes (6): ProxyServer, Background task: re-download stale adblock lists and hot-swap rules., Shut down all listeners and release relay resources., Return the IP to SNI-rewrite `host` through, or None.          Order of preced, Return override IP for host if defined in config 'hosts', else None., Return True if host should use the raw direct Google shortcut.

### Community 8 - "Server Proxyserver Support"
Cohesion: 0.16
Nodes (12): Read decrypted/origin-form HTTP requests and relay them., Return True if url matches any entry in _relay_url_patterns.          Pattern, Forward an HTTP request to its real origin via the SNI-rewrite path., Choose optimal relay strategy based on request type.          - If relay_url_p, Heuristic: is this URL likely a large file download?, cors_preflight_response(), has_unsupported_transfer_encoding(), header_value() (+4 more)

### Community 9 - "Server Proxyserver Do"
Cohesion: 0.15
Nodes (9): StreamReader, StreamWriter, Task, Serve the MITM CA certificate so LAN devices can install it., Route a target connection through the Apps Script relay., Connect with IPv4-first resolution and clearer failure reporting., Pipe raw TLS bytes directly to the target server.          connect_ip override, MITM-decrypt TLS from browser, then re-encrypt toward connect_ip         using (+1 more)

### Community 10 - "Domain Fronter Domainfronter"
Cohesion: 0.14
Nodes (9): Task, Close all pooled connections (they may be stale after errors)., Create a task and keep a strong reference for clean cancellation., Keep the Apps Script container warm via H1 when H2 keepalive is absent., Submit a request to the batch collector. Returns raw HTTP response., Two-tier batch window: 15ms micro + 120ms macro.          Single requests (lin, Send a batch of requests, split across H2 connections for parallel throughput., Fallback: relay a single request from a failed batch. (+1 more)

### Community 11 - "Vps Exit Node"
Cohesion: 0.15
Nodes (14): _collect_headers(), _ExitNodeHandler, main(), Return a clean header dict, dropping hop-by-hop and proxy headers., Return True only for plain http:// or https:// URLs (no localhost / LAN)., Collect HTTP response headers, preserving all values for duplicate names., Perform the outbound HTTP/HTTPS request and return a relay-JSON dict., Health-check endpoint — returns a friendly JSON status. (+6 more)

### Community 12 - "Logging Utils Prettyformatter"
Cohesion: 0.16
Nodes (11): LogRecord, _AsyncioNoiseFilter, configure(), _install_asyncio_noise_filter(), PrettyFormatter, print_banner(), Pretty, column-aligned, color-aware logging for MasterHttpRelayVPN.  Zero extr, Column-aligned formatter with optional ANSI colors. (+3 more)

### Community 13 - "Adblock Cache Parsehoststexttests"
Cohesion: 0.19
Nodes (15): Path, _cache_is_stale(), _cache_path(), _fetch(), load_all(), parse_hosts_text(), Adblock hosts list loader.  Downloads and caches domain blocklists at startup,, Blocking HTTP GET — intended to run inside asyncio.to_thread(). (+7 more)

### Community 14 - "Domain Fronter Domainfronter"
Cohesion: 0.16
Nodes (8): SSLContext, Background: open connections in parallel to refill empty pool., Open one TLS connection and add it to the pool., Continuously maintain healthy pool levels in background., Cancel background tasks and close all pooled / H2 connections., Open a TLS connection to the CDN.          - TCP_NODELAY is set on the underly, Round-robin the next SNI from the rotation pool., Get a healthy TLS connection from pool (TTL-checked) or open new.

### Community 15 - "Setup Configure Config"
Cohesion: 0.37
Nodes (15): bold(), _c(), configure_apps_script(), configure_network(), cyan(), dim(), green(), load_base_config() (+7 more)

### Community 16 - "Domain Fronter Domainfronter"
Cohesion: 0.14
Nodes (7): Pick a stable Apps Script ID for a host or fallback to round-robin.          W, Get the Apps Script endpoint path (/dev or /exec)., Round-robin across script IDs for load distribution.          Skips script IDs, One pass of the probe loop — re-validate every still-blacklisted SID., Background loop: every uniform(MIN, MAX) seconds re-probe blacklisted SIDs., Return True if a successful racer's bytes are actually an Apps         Script p, Pick up to `parallel_relay` distinct non-blacklisted script IDs.          The

### Community 17 - "Domain Fronter Domainfronter"
Cohesion: 0.14
Nodes (6): Return a point-in-time snapshot of traffic + script health., Periodically log top hosts by bytes. DEBUG-level, low overhead., Pre-open TLS connections in the background. Never blocks relay()., Start warmup and wait until the initial pool-open phase finishes.          Ret, Open WARM_POOL_COUNT connections in parallel — failures are fine., Log execution usage every N seconds, only when the count changed.

### Community 18 - "Exit Node Architecture"
Cohesion: 0.15
Nodes (14): Exit Node Deployment (FA), Exit Node Deployment, Apps Script Relay, Architecture, Exit Node, Local Proxy, Configuration, Getting Started (+6 more)

### Community 19 - "Domain Fronter Domainfronter"
Cohesion: 0.15
Nodes (8): BaseException, StreamReader, StreamWriter, Background: reconnect any H2 pool members that dropped.          Called after, Follow up to 5 HTTP redirects on an existing H1 connection.          307/308 p, Send multiple requests in one POST using Apps Script fetchAll., Return True only for genuine H2 *transport* failures.          Apps Script req, Return a connection to the pool if still young and healthy.

### Community 20 - "Support Proxysupporttests Server"
Cohesion: 0.20
Nodes (6): Intercept TLS, decrypt HTTP, and relay through Apps Script., is_ip_literal(), parse_content_length(), True for IPv4/IPv6 literals (strips brackets around IPv6)., Return Content-Length or 0. Matches only the exact header name., ProxySupportTests

### Community 21 - "Domain Fronter Domainfronter"
Cohesion: 0.25
Nodes (4): Exception, Connect all HTTP/2 transports in the pool., Connect H2, pre-warm the Apps Script container, start keepalive., Send periodic pings to keep Apps Script warm + H2 connection alive.

### Community 22 - "Support Responsecache Responsecacheparsettltests"
Cohesion: 0.28
Nodes (4): Simple LRU response cache for relayable static responses., Determine cache TTL from response headers and URL., ResponseCache, ResponseCacheParseTtlTests

### Community 23 - "Readme Architecture Configuration"
Cohesion: 0.29
Nodes (7): Architecture, Configuration, Domain Fronting, Exit Node, MasterHttpRelayVPN (FA), LAN Sharing, MasterHttpRelayVPN

### Community 24 - "Cloudflare Worker Decodebase64tobytes"
Cohesion: 0.53
Nodes (5): decodeBase64ToBytes(), encodeBytesToBase64(), fetch(), sanitizeHeaders(), STRIP_HEADERS

### Community 25 - "Setup Vps Exit"
Cohesion: 0.60
Nodes (5): error(), header(), info(), setup_vps_exit_node.sh script, warn()

### Community 26 - "Domain Fronter Domainfronter"
Cohesion: 0.33
Nodes (3): Split lst into n roughly-equal contiguous chunks (no empty chunks)., Extract the lowercase file extension from a URL path (no query)., Build sub-batches that isolate heavy (binary) from light requests.          A

## Knowledge Gaps
- **30 isolated node(s):** `STRIP_HEADERS`, `STRIP_HEADERS`, `start.sh script`, `graphify (Rule)`, `graphify (Workflow)` (+25 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **18 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `DomainFronter` connect `Domain Fronter Domainfronter` to `Response Fronting Support`, `H2 Transport H2transport`, `Domain Fronter Domainfronter`, `Server Proxyserver Direct`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`?**
  _High betweenness centrality (0.369) - this node is a cross-community bridge._
- **Why does `ProxyServer` connect `Server Proxyserver Direct` to `Ip Lan Google`, `Domain Fronter Domainfronter`, `Support Socks5`, `Server Proxyserver Support`, `Server Proxyserver Do`, `Support Proxysupporttests Server`, `Support Responsecache Responsecacheparsettltests`?**
  _High betweenness centrality (0.207) - this node is a cross-community bridge._
- **Why does `H2Transport` connect `H2 Transport H2transport` to `Response Fronting Support`, `Domain Fronter Domainfronter`, `Domain Fronter Domainfronter`?**
  _High betweenness centrality (0.090) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `DomainFronter` (e.g. with `ProxyServer` and `.__init__()`) actually correct?**
  _`DomainFronter` has 4 INFERRED edges - model-reasoned connections that need verification._
- **Are the 4 inferred relationships involving `ProxyServer` (e.g. with `_run()` and `MITMCertManager`) actually correct?**
  _`ProxyServer` has 4 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `H2Transport` (e.g. with `DomainFronter` and `ScriptDeploymentError`) actually correct?**
  _`H2Transport` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `STRIP_HEADERS`, `STRIP_HEADERS`, `Return a clean header dict, dropping hop-by-hop and proxy headers.` to the rest of the system?**
  _206 weakly-connected nodes found - possible documentation gaps or missing edges._