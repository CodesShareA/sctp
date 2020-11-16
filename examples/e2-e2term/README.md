# e2

e2 is a sctp example that shows how you can send/recv e2 messages.
In this example, there are 2 types of peers: **e2_term** and **e2**.

**e2_term** will always send `e2_term <seq_number>` messages to **e2** and receive `e2 <seq_number>` messages from **e2**.

**e2** will always receive `e2_term <seq_number>` from **e2_term** and send `e2 <seq_number>` messages to **e2_term**.

## Instruction

### Build e2_term and e2

```sh
make
```

### Run e2

```sh
./e2
```


### Run e2_term

```sh
./e2_term
```