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

## Configuration Change

XMP Profile 1 was selected in UEFI/BIOS.

The profile specifies:
- Transfer rate: DDR4-3200 MT/s
- Timings: 16-18-18-36
- DRAM voltage: 1.35 V

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
