---
image: quantum-computer.jpg
layout: image
transition: none
---

<Center>
    <h1 style="background-color:rgba(0,0,0,0.6)">Post-Quantum Cryptography</h1>
</Center>

<div class="abs-br m-6 text-xl">
    Photo by <a href="https://www.flickr.com/photos/feuilllu/">Pierre Metivier</a> on <a href="https://www.flickr.com/photos/feuilllu/46700983592">Flickr</a>
</div>

---
layout: two-cols-header
---

# Post-Quantum Cryptography

Effects of Quantum Computers on Algorithms

::left::

<v-click>

## Symmetric (ex: AES)

Halves effective strength

</v-click>

::right::

<v-click>

## Asymmetric (ex: RSA)

Breaks the cipher

</v-click>

::bottom::

<v-click>

TLS uses Asymmetric Cryptography to negociate Ephemeral (Session) Symmetric Cryptography

🪦

</v-click>

---
layout: two-cols-header
---

# First Selected Algorithms: Crystals-Lattice

::left::

<v-click at=1>
    <h2>Dilithium</h2>
</v-click>

<v-click at=2>

<img src="/ncc-1701.webp" />

Source: Memory Alpha

</v-click>

::right::

<v-click at=1>

## Kyber

</v-click>

<v-click at="2">

<img src="/saber.webp" />

Source: Wookiepedia

</v-click>

::bottom::

<v-click at="2">

I'm not as courageous as [Rendle to confuse them](https://youtu.be/pJPBL8auiy0?si=sCwD2Dnmhv5IpekR&t=3001)!

</v-click>

---
layout: two-cols-header
---

# First Selected Algorithms: Crystals-Lattice

::left::

## Dilithium

<v-click>

### ML-DSA

Module-Lattice-Based Digital Signature Algorithm

FIPS-204

</v-click>

::right::

## Kyber

<v-click>

### ML-KEM

Module-Lattice-Based Key Encapsulation Mechanism

FIPS-203

</v-click>

---
layout: two-cols-header
---

# Timeline

::left::

<v-click>

## 2030

PQC Support SHOULD Be Enabled

</v-click>

::right::

<v-click>

## 2035

Traditional Cryptography is Deprecated

</v-click>