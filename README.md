# Scryfall Analysis with Naive Bayes

## Introduction

Scryfall is a website which mains a comprehensive database for all cards in the card game "Magic: The Gathering". We will use the public available data to create a model which will attempt to predict what color it is, based on the oracle tags (a community project that classifies card effects).

This analysis is relevant because each color in Magic has a specific set of effects from which the cards can pull from. For example, effects that can directly deal damage are overwhelming found on red cards, but they also sometimes appear on black cards.