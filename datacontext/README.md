
## Data Context

What does Data Context does for you throughout using Great Expectations:
1. Setup
- Provides methods to configure Stores, plugins, and Data Docs.

2. Connect to data 
- Provides methods to create, configure, and access Datasources

3. Create Expectations
- Provides methods to create, configure and access Expectations and Profilers.
4. Validate Data
- Provides methods to create, configure and access Checkpoints.


In addition to all of that,  it will internally manage your Metrics, Validation Results, and the contents of your Data Docs for you!

So it is important to initialize a data context when dealing with Great Expectations.

### Steps to configure Instantiate a DataContext

Here, we are importing the great_expectations library package and loading DataContext into memory using the get_context() method.
> import great_expectations as gx </br>
> context = gx.get_context()

