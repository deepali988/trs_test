## Background

We like coffee.

So we built an app to fetch coffee for people from our favourite barista.

The app keeps track of coffee ordered; what the balance is for each user; what users have paid for already; and what is still owed.

## Data

We've got the following data

- `data/prices.json` - provided by our barista. Has details of what beverages are available, and what their prices are.
- `data/orders.json` - list of beverages ordered by users of the app.
- `data/payments.json` - list of payments made by users paying for items they have purchased.

## Requirements

- Load the list of prices
- Load the orders
  - Calculate the total cost of each user's orders
- Load the payments
  - Calculate the total payment for each user
  - Calculate what each user now owes
- Return a JSON string containing the results of this work.

(see `spec/coffee_app_integration_spec.rb` for specific examples)

## Getting Started

Create a directory to work on your project. Copy `trs_coding_task.tar.gz` into your project directory. To extract the project files, run:
```
tar -xzvpf trs_coding_task.tar.gz
```

trs Espresso requires ruby and bundler to be installed. Before you begin; install the dependencies by running `bundle`.
Once the dependencies have been installed you'll have a few commands available:

- `bundle exec rake`  : Will attempt to run your application and print output to the terminal.
- `bundle exec rspec` : Runs the test suite, we've added a few integration tests to get you started, but you'll probably want to add more as you work.

Include the `.git` directory in the packaged .tar.gz file you send to us.

## Do not publish our task

It should go without saying that we don't want other candidates to see our
task or previous submissions.
