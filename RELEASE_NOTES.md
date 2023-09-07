1.2.0
- 2023-06-16 ROCK-4: Implement bedrock::telemetry::metrics
- 2023-08-29 Remove unnecessary cast
- 2023-08-23 ZTC-885: Updates heap profiling code slightly to be usable by oxy
- 2023-06-19 Fix unused_variables lint
- 2023-08-02 Document SpanScope and move it out of internal module
- 2023-08-01 Do not drop heap profile temp file before reading completion
- 2023-08-01 ROCK-5 Implement jemalloc-related functionality

1.1.0
- 2023-07-26 Release 1.1.0
- 2023-07-24 ROCK-16: Add 'jaeger_reporter_bind_addr' to TracingSettings
- 2023-07-04 Adds cargo-release and git-cliff config

1.0.3
- 2023-07-03 Version 1.0.3
- 2023-06-28 Use workspace metadata for crates

1.0.2
- 2023-06-27 Version 1.0.2
- 2023-06-27 Removes cyclical dependency

1.0.1
- 2023-06-27 Release 1.0.1
- 2023-06-27 Updates cfsetup.yaml to support registry
- 2023-06-27 Specifies registry in workspace toml

1.0.0
- 2023-06-23 ETI-942: Fixes indentation of cfsetup publish builddeps
- 2023-06-23 Release 1.0.0
- 2023-06-23 ETI-942: Publish crate to internal registry
- 2023-06-20 Rename `seccomp` module to `security`.
- 2023-06-15 Add a few more common allow lists used by Cloudflare apps
- 2023-06-14 ROCK-3 Implement seccomp filter initialization
- 2023-06-13 chore: remove shih-chiang from CODEOWNERS
- 2023-06-09 ROCK-3  Seccomp: implement allow lists
- 2023-06-07 Fix syscall doc links
- 2023-06-06 Remove lohith from code-owners
- 2023-06-06 ROCK-3 Generate syscalls enums
- 2023-06-05 Implement with_test_telemetry macro
- 2023-06-03 Test API changes.
- 2023-06-02 ROCK-13 Finish telemetry documentation
- 2023-05-31 Set ipv6 reporter addr if agent is set to ipv6
- 2023-05-25 Add links whenever we create a new trace and we have one ongoing
- 2023-05-30 Settings: add PartialEq impl between std::net types and wrappers
- 2023-05-29 Add doctests for with_forked_trace and start_trace
- 2023-05-25 ZTC-881 Allow overriding sampling ratio for started trace
- 2023-05-24 Expose SerializableTraceState
- 2023-05-20 ROCK-9, ROCK-13 Part 1: Add the rest of the tracing API and document telemetry
- 2023-05-12 Move settings macro into the settings module
- 2023-05-12 ROCK-9, ROCK-10 Implement tracing internals and testing
- 2023-05-11 GATE-4093: change bedrock package version to use the standard indexed field
- 2023-05-04 ROCK-2 Implement logging
- 2023-05-02 Get rid of owned keys feature in slog to not introduce breaking changes
- 2023-05-02 ROCK-11 Add toggle to disable Debug impl in Settings macro
- 2023-04-27 Add feature combination testing
- 2023-04-26 ROCK-8 Implement test log and log drains
- 2023-04-18 Remove println leftover in test
- 2023-04-17 Implement settings
- 2023-04-12 Set up repo
- 2023-04-12 Initial commit
