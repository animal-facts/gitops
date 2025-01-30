# Use a Flyway version that works for your environment (including ARM if on Raspberry Pi)
FROM flyway/flyway@sha256:6f913eb7df2cfc1c51c93034c6e6eae35ab0cd8dd1c3d0cdd11b9f6c1cf64cc1 # 9.22.0 arm/v7

# Copy local migrations into the default Flyway SQL directory
COPY migrations/ /flyway/sql/
