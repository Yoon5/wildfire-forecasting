# Pre-trained Checkpoint Files

| Checkpoint file                                                               | Input Variable(s)  | Input Days | Output Variable(s) | Output Days | Preprocessing                                               | No. of epochs |
|-------------------------------------------------------------------------------|--------------------|------------|--------------------|-------------|-------------------------------------------------------------|---------------|
| [epoch_41_100.ckpt](2_1/epoch_41_100.ckpt)  | T2, TP, RH, WSpeed | 2          | FWI-Reanalysis     | 1           | - FWI between [0,1] rounded off<br>- Box-cox transformation | 100           |
| [epoch_91_100.ckpt](2_1/epoch_91_100.ckpt)  | T2, TP, RH, WSpeed | 2          | FWI-Reanalysis     | 1           | - Undersampling for FWI < 10<br>- Box-cox transformation    | 100           |
| [epoch_83_100.ckpt](4_10/epoch_83_100.ckpt) | T2, TP, RH, WSpeed | 4          | FWI-Reanalysis     | 10          | - Undersampling for FWI < 10<br>- Box-cox transformation    | 100           |
| [epoch_99_100.ckpt](4_10/epoch_99_100.ckpt) | T2, TP, RH, WSpeed | 4          | FWI-Reanalysis     | 10          | - FWI between [0,1] rounded off<br>- Box-cox transformation | 100           |