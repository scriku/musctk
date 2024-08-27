This is a modified version of Superconducting Toolkit (SCTK).
Calculation mode "lambda_mu_k" now only calculate mu, and the phonon part are skipped.
Original repository: https://github.com/mitsuaki1987/sctk/tree/develop


Installation
``` bash
$ git clone https://gitlab.com/QEF/q-e.git
$ cd q-e
$ git checkout 96cdd5ac6af9c060be392a95f14dbcbca5c1a890
$ git clone https://github.com/scriku/musctk.git
$ patch -p1 < musctk/patch.diff
$ ./configure --enable-openmp
$ make pw ph pp
$ cd sctk
$ make
```

