# Courier Fraud Checker BD for Laravel

A Laravel package to detect potential fraudulent orders by checking customer delivery behavior through Pathao and Steadfast courier services in Bangladesh.

## 🔧 Configuration

Add these environment variables to your `.env` file:

```env
# Pathao Credentials
PATHAO_USER=your_pathao_email
PATHAO_PASSWORD=your_pathao_password

# Steadfast Credentials
STEADFAST_USER=your_steadfast_email
STEADFAST_PASSWORD=your_steadfast_password
```