Pinto-Demo
==========

Tools and data for my live Pinto demonstrations


Prerequisites
=============


* Install a perl (preferably 5.16.3 or later).  I recommend using perlbrew

```bash
curl -L http://install.perlbrew.pl | bash
perlbrew install perl-5.16.3
perlbrew use perl-5.16.3
```

* Install cpanm

```bash
curl -L http://cpanmin.us | perl - App::cpanminus
```
* Install pinto

```bash
curl -L http://getpinto.stratopan.com | bash
```

* Install cleo

```bash
cpanm App::Cleo
```

Running The Demo
================

```bash
git clone git@github.com:thaljef/Pinto-Demo.git
cd Pinto-Demo
cleo demo.cleo
```
