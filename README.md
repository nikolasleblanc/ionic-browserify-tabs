# Ionic Browserify Boilerplate (Tabs)

Based off the tabs ionic template, this restructures the code to allow for the use of browserify, via browserify-shim.

## Instructions

### Step 1: Clone the repo

```
git clone git@github.com:nikolasleblanc/ionic-browserify-tabs.git
```

### Step 2: Install all node_modules

```
npm install
```

### Step 3: Run browserify

```
browserify -d www/js/app.js -o www/js/app.bundle.js
```

### Step 4: Run ionic serve

```
ionic serve
```

## What now?

You've now got a working boilerplate of ionic primed for required modules via browserify. Because `ionic serve` isn't setup to re-browserify your javascript, you'll have to either:

- Exit `ionic serve` and repeat step 3, or
- Opt out of `ionic serve` and build your own gulp file to watch the files, run sass, and re-browserify


