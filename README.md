# Syrablus API Routes and Specifications

This document provides a detailed breakdown of the API routes available in the Syrablus project, extracted from the interactive Swagger UI documentation. Each section outlines the endpoints, their methods, and a brief description of their functionality.




## Authentication Routes

This section details the API endpoints related to user authentication and registration.

| Method | Endpoint                  | Description         |
|--------|---------------------------|---------------------|
| POST   | `/{url}/users/login`      | User login          |
| POST   | `/{url}/users/register`   | User registration   |




## User Wallet Routes

This section outlines the API endpoints for managing user wallets.

| Method | Endpoint                  | Description         |
|--------|---------------------------|---------------------|
| GET    | `/{url}/users/wallet`     | Get user wallets    |




## Manufacturers Routes

This section details the API endpoints for retrieving manufacturer information.

| Method | Endpoint                          | Description               |
|--------|-----------------------------------|---------------------------|
| GET    | `/{url}/users/manufacturers`      | Get all manufacturers     |
| GET    | `/{url}/users/manufacturers/search` | Search manufacturers by name |




## Main Service Routes

This section outlines the API endpoints for the main service.

| Method | Endpoint                      | Description         |
|--------|-------------------------------|---------------------|
| GET    | `/{url}/users/main-service`   | User main service   |




## Cars Routes

This section details the API endpoints for managing user cars.

| Method | Endpoint                  | Description         |
|--------|---------------------------|---------------------|
| GET    | `/{url}/users/cars`       | Get user cars       |
| POST   | `/{url}/users/cars`       | Create new car      |




## Brands Routes

This section outlines the API endpoints for managing brands and their versions.

| Method | Endpoint                          | Description                     |
|--------|-----------------------------------|---------------------------------|
| GET    | `/{url}/users/brands`             | Get brands of the manufacturer ID |
| GET    | `/{url}/users/cars/brand-versions`| Get brand version by brand ID   |
| GET    | `/{url}/users/brands/search`      | Search brands by name           |




## Address Routes

This section details the API endpoints for managing user addresses.

| Method | Endpoint                      | Description         |
|--------|-------------------------------|---------------------|
| GET    | `/{url}/users/address`        | Get user address    |
| POST   | `/{url}/users/address/lat-long` | Create new address  |





live
