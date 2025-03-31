API Setup Guide

This guide will help you obtain the necessary API keys for full functionality of the AI-Powered Personal Finance Tracker.

Required APIs

The finance tracker requires several API keys to enable all features:

1. OpenAI API Key - For AI-powered insights and natural language processing
2. UPI Client ID and Secret - For integration with Indian UPI payment system
3. Account Aggregator API Key - For connecting with Indian banking framework

 How to Obtain API Keys

 OpenAI API Key

1. Visit [OpenAI's platform](https://platform.openai.com/signup)
2. Create an account or sign in
3. Navigate to the API section
4. Create a new API key
5. Copy the key and add it to your `.env` file as `OPENAI_API_KEY=your_key_here`

UPI Client ID and Secret (For Indian Developers)

For development and testing, you can use:

1. NPCI Developer Portal:
   - Visit [NPCI Developer Portal](https://developer.npci.org.in/)
   - Apply for developer credentials through the portal
   - Complete the verification process
   - Receive your Client ID and Secret

2. Alternative: Use UPI Payment Service Provider:
   - Register with a Payment Service Provider (PSP) like Razorpay, Cashfree, or PayU
   - Navigate to their Developer/API section
   - Generate API credentials for UPI integration
   - Use these credentials in your `.env` file

Account Aggregator API Key

For the Account Aggregator framework integration:

1. Register with Sahamati:
   - Visit [Sahamati](https://sahamati.org.in/)
   - Apply as a Financial Information User (FIU)
   - Complete the technical integration documentation
   - Receive your API access credentials

2. Alternative: Third-party Providers**:
   - Services like Finvu, OneMoney, or Perfios provide simplified AA connectivity
   - Register as a developer on their platforms
   - Generate API keys for their services
   - Use these keys in your `.env` file

Testing Without API Keys

The application includes fallback mechanisms to function with limited capabilities when API keys are not available:

1. Without OpenAI API: Basic rule-based financial insights will be provided
2. Without UPI/AA Integration: Manual transaction entry will be available

Security Best Practices

1. Never share your API keys or commit them to public repositories
2. Store keys in the `.env` file which is excluded from version control
3. Regularly rotate your API keys for enhanced security
4. Consider using environment variables for production deployment

Troubleshooting

If you encounter issues with API connectivity:

1. Verify the API key is correctly formatted
2. Check that your account has sufficient credits/permissions
3. Ensure you're using the correct endpoint URLs
4. Check your network connectivity and firewall settings

For persistent issues, contact the respective API provider's support team.