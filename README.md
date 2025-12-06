# sql-data-warehouse
This project showcases a complete end-to-end Data Warehouse built in SQL Server and organized using the Medallion Architecture (Bronze → Silver → Gold).
The goal was to take raw CRM and ERP datasets, clean and standardize them, and build an analytics-ready star schema suitable for reporting and BI tools.

# Project Overview

I designed this warehouse to understand how raw operational data moves through a modern ELT pipeline from ingestion, to transformation, to a clean analytical model. Starting from CSV and ERP source files, the project walks through loading, cleaning, modeling, and preparing data for insights.

# Purpose
This project demonstrates how to transform raw operational data into a clean, structured warehouse ready for analytics. It follows industry best practices and shows how an ELT workflow feeds into a reliable, scalable reporting model.

# Architecture

**Bronze — Raw Layer**

Loaded ERP & CRM CSV files directly into SQL Server
Stored raw data “as-is” for traceability

**Silver — Cleaned & Standardized**

Applied transformations to fix data quality issues
Cleaned and standardized fields, formats, and structures
Prepared unified tables ready for modeling

**Gold — Star Schema**

Built fact and dimension tables (Sales Fact, Customers, Products, etc.)
Designed for high-performance analytical queries and BI tools

# What This Project Includes

Full ELT pipeline (Extract → Load → Transform) using SQL
Data ingestion into Bronze, transformation in Silver, and modeling in Gold
Data cleansing, standardization, and integration of CRM & ERP sources
Star-schema data model ready for reporting and analytics

