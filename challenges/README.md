## Comando tar - P1

```sh
tar xvf challenges.tar.gz challenges/ 
```

## Comando CD - P2

```sh
cd challenges/ 
```

## Comando ls - P3

```sh
ls 
```

## Comando mkdir - P4
```sh
mkdir "foo"  
```

## Comando mkdir - P5

```sh
mkdir -p foo/bar/1/2/3 
```

## Comando rm - P6

```sh
rm -r foo/ 
```

## Comando echo - P7

```sh
echo "Hello World" 
```

## Comando touch - P8

```sh
touch hello.txt && echo "Hello World" > hello.txt 
```

## Comando touch - P9

```sh
touch empty.txt
```

## Comando rm - P10

```sh
rm empty.txt
```

## Comando cat - P11

```sh
cat > empty.txt 
```

## Comando expand - P12

```sh
expand > empty.txt  
```

## Comando cp - P13

```sh
cp hello.txt goodbye.txt
```

## Comando mv - P14

```sh
mv goodbye.txt hello_copy.txt
```

## Comando cat - P15

```sh
cat hello_copy.txt hello.txt 
```

## Comando cat - P16

```sh
cat hello_copy.txt hello.txt > 2_hellos.txt
```

## Comando pwd - P17

```sh
pwd
```

## Comando ls - P18

```sh
ls -l
```
## Comando echo - P19

```sh
echo "Hello Restrict" >> restricted.txt
```


## Comando ./ - P20

```sh
./hello_executable
```

## Comando chmod - P21

```sh
chmod 777 challenge_20
./challenge_20
```

## Comando chmod - P22

```sh
chmod 777 compile_me.c || ./compile_me.c 
```

## Comando tee - P23

```sh
./redirect | tee output.txt
```

## Comando date - P24

```sh
date
```

## Comando ps - P25

```sh
ps
```

## Comando lscpu - P26

```sh
lscpu
```

## Comando uname - P27

```sh
uname -r
```

## Comando grep - P28

```sh
cat bunch_of_files/* | grep "You found the needle in the haystack!"
```

## Comando head - P29

```sh
head -25 people.csv
```

## Comando tail - P30

```sh
tail -n 25 people.csv
```

## Comando diff - P31

```sh
diff greeting1.txt greeting2.txt 
```

## Comando sleep - P32

```sh
echo "Hello" && sleep 5 && echo "world" 
```

## Comando dd - P33

```sh
dd if=/dev/zero of=nullbytes count=1 bs=1M 
```

## Comando head - P34

```sh
head -c 2M /dev/urandom > random 
```

## Comando wc - P35

```sh
wc -l README.md 
```

## Comando tac - P36

```sh
tac README.md  
```

## Comando awk - P37

```sh
awk -F, '{print $2}' people.csv 
```

## Comando awk - P38

```sh
awk -F, '{print $2}' people.csv | sort -u | wc -l
```

## Comando awk - P39

```sh
awk -F, 'NR>1{print $2}' people.csv | sort -u | wc -l
```

## Comando awk - P40

```sh
awk -F, '{print $2}' people.csv | head -n -2 | tail -n+2 | sort -u| wc -l
```

## Comando awk - P41
```sh
awk -F, 'NR>1{print $2}' people.csv | sort -u | wc -l
```

## Comando awk - P42

```sh
awk -F, '/Josiah/ {print $4}' people.csv | wc -l
```

