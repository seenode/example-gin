# Deploy Gin on Seenode in Seconds

This is a minimal and production-ready Gin application configured for deployment on [Seenode](https://seenode.com).

### Deploy in Minutes
Check out our [Gin deployment guide](https://seenode.com/docs/services/web-services/framework-guides/go/gin/) for more details.

## How to Deploy on Seenode

1. **Connect Your Repository**: Visit the [Seenode dashboard](https://cloud.seenode.com), click **New Web Service**, and link this Git repository.
2. **Confirm Settings**:
    - **Build Command**: `go build -o app main.go`
    - **Start Command**: `./app`
3. **Deploy**: Hit **Create Web Service**.

Your Gin app will now be deployed and accessible via a public URL.

### Key Notes

- **Port Binding**: This example explicitly listens on port `80`. Make sure your code reflects that (`router.Run(":80")`).
- **Static Binary**: Go apps are compiled into a single binary, making deployments fast and reliable.
- **Seamless Scaling**: As demand increases, scale effortlessly from the Seenode dashboard.
