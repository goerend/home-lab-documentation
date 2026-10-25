# Desktop RAM Configuration and Validation

## Objective

Configure the installed Kingston DDR4 memory to operate at its rated 3200 MT/s transfer rate and assess stability using MemTest86.

## Test Environment

| Component | Details |
|---|---|
| CPU | AMD Ryzen 5 5600X, 6 cores / 12 threads |
| Motherboard | ASRock B550M PG Riptide |
| BIOS version | P3.90 |
| Memory | 32 GB Kingston DDR4, 2 × 16 GB |
| Memory model | KF3200C16D4/16GX |
| Operating system | Ubuntu 26.04.1 Desktop |
| Memory diagnostic tool | PassMark MemTest86 Free |
| MemTest86 version | 11.7 |

## Initial Configuration

The memory was initially operating at 2400 MT/s with the BIOS memory setting on Auto.

## Evidence 1 — Initial Configuration

The following screenshots document the memory configuration before enabling XMP Profile 1.

### Initial BIOS configuration

![Initial RAM configuration](evidence/01.0-initial-ram-configuration.jpeg)

![Additional initial RAM configuration](evidence/01.1-initial-ram-configuration.jpeg)

### Initial MemTest86 configuration

![MemTest86 at 2400 MT/s](evidence/memtest-2400-initial.jpeg)

The initial memory operating speed was recorded as 2400 MT/s with the BIOS memory setting on Auto. These screenshots establish the baseline for comparison with the subsequent XMP Profile 1 configuration.


## Configuration Change

XMP Profile 1 was selected in UEFI/BIOS.

The profile specifies:
- Transfer rate: DDR4-3200 MT/s
- Timings: 16-18-18-36
- DRAM voltage: 1.35 V

## Evidence 2 — XMP Profile 1 Configuration

XMP Profile 1 was enabled in UEFI/BIOS to configure the Kingston memory
for its rated DDR4-3200 MT/s transfer rate.

The selected profile specifies timings of 16-18-18-36 at 1.35 V.

### MemTest86 — Intermediate Result 1

![MemTest86 DDR4-3200 progress](evidence/02.0-memtest-3200-progress.jpeg)

### MemTest86 — Intermediate Result 2

![MemTest86 DDR4-3200 progress, second capture](evidence/02.1-memtest-3200-progress.jpeg)

Both screenshots document the test in progress. At the time of capture,
MemTest86 reported zero errors. These are intermediate results, not the
final stability-test outcome.

## Validation Procedure

1. Boot MemTest86 from USB media.
2. Confirm the detected memory capacity and operating speed.
3. Run the planned four-pass memory test.
4. Monitor the reported error count.
5. Record the final results before drawing a conclusion.

## Results

- Test status: In progress
- Configured transfer rate: 3200 MT/s
- Passes completed: Pending
- Errors: Zero reported in the latest recorded screenshot
- Final elapsed time: Pending

## Conclusion

To be completed after the planned test finishes.

A clean MemTest86 result provides evidence of memory stability under the tests performed, but does not guarantee stability under every workload.

## Lessons Learned

To be completed after reviewing the final results and reflecting on the configuration and testing process.
