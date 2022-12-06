---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
colorSchema: 'light'
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

## Escrow Protocol for Privacy-preserving 
## Payment Channel Network

LIU Mengling

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---

# Bitcoin
Global financial payment system, Decentralized

<br>
<br>
<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="image/BitcoinNode.jpeg">

<img border="rounded" src="image/blockchain.jpg">
<div class="cap">
Global Bitcoin Nodes Distribution
</div>
<div class="cap">
Centralized & Decentralized
</div>

</div>
<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->
<br>
<br>
<br>
<br>
<br>
<br>
<div class="ref">
  Reference: <br>
  1. Global Bitcoin Nodes Distribution, https://bitnodes.io/ <br>
  2. BlockChain Arche, https://mlsdev.com/blog/156-how-to-build-your-own-blockchain-architecture
</div>

<style>
h1 {
  background-color: #a6b9e1;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Scalability Issue
Majority vote, Low transaction rate

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/scal.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Scalability Issue
Majority vote, Low transaction rate

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/scal2.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# The Challenge in the Dispute Handling
Decentrialized, TTP

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/disputehandle.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Promising Approaches to the Scalability Issue
Payment Channel,Layer-2 Protocol,Off-chain payment, Create the channel
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/pcncreate.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Promising Approaches to the Scalability Issue
Payment Channel,Layer-2 Protocol,Off-chain payment, Update the channel
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/pcnupdate.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Promising Approaches to the Scalability Issue
Payment Channel Networks, Multi-hop Payment, No direct channel
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/pcn.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Atomicity in Payment Channel Networks
The partial failure can cause coin losses for users.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/pcnato.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Lightning Network
Hash time lock contract (HTLC), Set up HTLC
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/lnhtlc.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Lightning Network
Settle the payment.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/htlcunlock.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Security Issue in Payment Channel Networks
The Wormhole Attack (Malavolta et al. NDSS 2019).
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/warmhole.jpg" width="750">
</div>

<div class="ref">
  Reference: <br>
  Malavolta, G., Moreno-Sanchez, P., Schneidewind, C., Kate, A., Maffei, M.: Anonymous Multi-Hop Locks for Blockchain Scalability and Interoperability. In: Proceedings 2019 Network and Distributed System Security Symposium. Internet Society, San Diego, CA (2019). https://doi.org/10.14722/ndss.2019.23330.
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>


---

# Security Issue in Payment Channel Networks
The Wormhole Attack (Malavolta et al. NDSS 2019).
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/warmholedetails.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Privacy Issue in Payment Channel Networks
Global hash.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/privacy.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Inefficiency in Current State-of-the-Art Solutions

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/ineamhl.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol
Escrow phase.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/escrow1.jpg" width="760">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol
Deliver phase.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/escrow2.jpg" width="760">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol
When the dispute appears.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/escrow3.jpg" width="760">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Inefficiency in State-of-the-Art Escrow Protocol

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/inees.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Our Contribution

<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/contribution.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol for Privacy-preserving Payment Channel Network
Setting up phase.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/our1.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol for Privacy-preserving Payment Channel Network
Locking phase.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/our2.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Escrow Protocol for Privacy-preserving Payment Channel Network
Settleing phase.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/our3.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Performance Comparison
Escrow protocol.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/comes.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>

---

# Performance Comparison
AMHL.
<div grid="~ cols-1 gap-2" m="-t-1">
  <img border="rounded" src="image/comamhl.jpg">
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #a6b9e1 10%, #244184 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.ref {
  font-size: xx-small;
}
.cap {
  font-size: small;
}
</style>


