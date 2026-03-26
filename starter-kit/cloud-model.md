# Cloud Service Model Choice

## Selected Model: PaaS (Platform as a Service)

### Why PaaS?
- Simplifies operations (no manual VM patching or OS maintenance)
- Provides built-in scalability, load balancing, backups, and monitoring
- Reduces DevOps overhead for a small engineering team
- Faster deployment cycles

### Why Not IaaS?
- Requires VM administration
- More complexity for networking, patching, and scaling

### Why Not SaaS?
- KijaniKiosk needs a custom application, not an out-of-the-box tool

**Conclusion:** PaaS provides the ideal balance between flexibility and reduced operational load.

---

## **Evidence**
- Cloud reasoning documented as part of the starter-kit files under `/starter-kit/cloud-model.md`
- Decision committed in the `feature/starter-kit-files` branch