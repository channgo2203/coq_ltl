## Introduction

Formalization of Linear Temporal Logic (LTL) in Coq.

## Path Encoding

Paths are represented by infinite co-inductive lists, 
e.g., a streams. 

## Temporal Operator Encoding

Temporal operators are encoded by co-inductive or 
inductive types depending on whether they are greatest 
or least fix-points.