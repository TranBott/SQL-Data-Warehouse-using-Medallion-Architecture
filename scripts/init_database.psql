-- =============================================================
-- Create Database and Schemas
-- =============================================================

-- Drop and recreate the DataWarehouse database
DROP DATABASE IF EXISTS "DataWarehouse" WITH (FORCE);

CREATE DATABASE "DataWarehouse";

-- Connect to DataWarehouse
\c "DataWarehouse"

-- Create Schemas
CREATE SCHEMA IF NOT EXISTS bronze;
CREATE SCHEMA IF NOT EXISTS silver;
CREATE SCHEMA IF NOT EXISTS gold;
