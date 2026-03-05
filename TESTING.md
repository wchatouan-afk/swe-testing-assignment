{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Strat\'e9gie de Test - Quick-Calc\
\
## Concepts du cours\
- **Pyramide des tests** : J'ai privil\'e9gi\'e9 les tests unitaires (8) pour la base, avec quelques tests d'int\'e9gration (2).\
- **Black-box Testing** : Mes tests v\'e9rifient que 5+3 donne bien 8 sans analyser le code interne.\
- **Regression Testing** : Cette suite permet de v\'e9rifier qu'une modification future ne cassera pas les fonctions de base.\
\
## R\'e9sultats\
| Test | Type | Statut |\
|------|------|--------|\
| Addition/Soustraction/Mult/Div | Unitaire | Pass |\
| Division par z\'e9ro | Unitaire (Edge Case) | Pass |\
| Sc\'e9nario utilisateur complet | Int\'e9gration | Pass |}