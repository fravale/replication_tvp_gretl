# replication_tvp_gretl

IN PROGRESS...

***************************************************************

Replication package:

"Linear models with time-varying parameters: a comparison of different
approaches"

by Riccardo "Jack" Lucchetti and Francesco Valentini

***************************************************************

Software requirements: gretl 2023b or above.

Additional gretl packages:

- FLS (0.1 or above);

- ketvals (1.1 or above);

- TVC (1.2 or above).


Additional scripts:

- tvar_kf.inp : it include routinres to perform the
Kalman filter (KF) estimation;

- tvc_mod.inp: a fork of the TVC functions. All visual and
supplemental output suppressed to speed up Monte Carlo simulations.

***************************************************************

Scripts for replication:

- 1_simple.inp --> replicates results in Section 3.1;
- 2_mc_tvp.inp --> replicates results in Table 2;
- 3_cpu_time.inp --> replicates results in Table 4 (up to hardware!)
- 4_application.inp --> replicates results in Section 4;
- 5_mc_tvp_rob.inp --> replicates results in Table 3;
- 6_application_static.inp --> TODO

***************************************************************
