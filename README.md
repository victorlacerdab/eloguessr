# eloguessr

# Introduction

This repository covers the implementation of a simple model that predicts the mean ELO of a chess match (that is, the mean ELO of the two players) given text data. It was inspired by the popular series "ELO Guesser" by GothamChess.
It is meant to be an exercise in how to use Transformers for a regression task. We cover the entire pipeline, from data acquisition and pre-processing to model building and training.

# Data sources

We use data collected from Lichess' open database (https://database.lichess.org/) and, for quick access to high rated ELO games, we used the Lichess Elite Database (https://database.nikonoel.fr/) compiled by Niko Noel.

