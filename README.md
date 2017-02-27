# Miniflow Forward Method (Udacity SDCND T1L7C7)
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## Synopsis

This repository contains code used in Lesson 7 - Chapter 7 of Udacity's Self Driving Car Nanodegree (Term 1).

## Goal

The goal of the quiz is to define the forward method in Miniflow (a very basic version of TensorFlow) in the Linear class. The method should produce output depending on the weighted sum of inputs + bias according to the following linear equation.

![Linear Equation](https://gtoran.github.io/repository-assets/udacity-sdcnd-t1l7c7-learning-and-loss/linear-equation.png)

## Expected Results

The supplied nn.py file creates the following:

feed_dict = {
    inputs: [6, 14, 3],
    weights: [0.5, 0.25, 1.4],
    bias: 2
}

The expected output is 12.7, resulting from the following:

`(6 x 0.5) + (14 x 0.25) + (3 x 1.4) + 2`
