# Interfaccia grafica per GNUDO, realizzata con qt e c++


## Download dei sorgenti

Questo progetto utilizza delle librerie integrate come git submodule. Pertanto __non deve essere scaricato come zip da github__, perché tali librerie non verrebbero incluse. La procedura corretta attualmente è questa:

```bash
git clone https://github.com/matteoalessiocarrara/GNUDO-cpp-ui-qt.git
cd GNUDO-cpp-ui-qt
git submodule update --init --recursive
```

## Compilazione

```bash
mkdir build && cd build
qmake .. -r && make
```

## Aggiornamenti

È possibile iscriversi al canale [telegram](https://telegram.me/matteoalessiocarrara) 
od alla comoda pagina [facebook](https://www.facebook.com/matteoalessiocarrara).

