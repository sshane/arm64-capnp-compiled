# capnproto compiled for arm aarch64


Configured with:
----

```bash
./configure --with-external-capnp --host=aarch64-linux-gnu --prefix=/home/shane/capnp/capnproto/c++/dst
```

Then a clean to fix custom install dir issue:
----

```bash
make clean
```

Compile without checking (since we would try to run an arm binary on x86):
----

```bash
make -j24
```

Install to local dir for easy gathering:

```bash
sudo make install
```

