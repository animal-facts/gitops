# Use a Flyway version that works for your environment (including ARM if on Raspberry Pi)
# 9.22.0 arm/v7
#FROM flyway/flyway@sha256:6f913eb7df2cfc1c51c93034c6e6eae35ab0cd8dd1c3d0cdd11b9f6c1cf64cc1
FROM flyway/flyway:9.22.0

# Copy local migrations into the default Flyway SQL directory
COPY migrations/ /flyway/sql/

# Install PostgreSQL client tools
RUN apt-get update && apt-get install -y postgresql-client && rm -rf /var/lib/apt/lists/*
