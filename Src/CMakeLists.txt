cmake_minimum_required(VERSION 3.21)

project (
  "project1"
  VERSION 1.0
  DESCRIPTION "project1"
  LANGUAGES C)

add_executable (project1)
target_sources (project1 PRIVATE main.c)
