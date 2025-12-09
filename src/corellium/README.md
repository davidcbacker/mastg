# automatecorellium

https://github.com/davidcbacker/automatecorellium

# Setup Instructions

1. Add the appropriate `yaml` files and copy `functions.sh` to your GitHub repository
2. Set the `CORELLIUM_API_TOKEN` secret ([see Corellium documentation](https://support.corellium.com/administration/api-token), [GitHub documentation](https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/use-secrets))
3. Set the `CORELLIUM_API_ENDPOINT` actions variable to the domain for your server ([see GitHub documentation](https://docs.github.com/actions/learn-github-actions/variables))
   - For example, `https://exampledomain.enterprise.corellium.com` or `https://corellium.examplecompany.com`
4. Set the `CORELLIUM_DEFAULT_PROJECT` actions variable
