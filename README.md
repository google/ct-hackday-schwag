# CT Display Schwag

This is a driver for an LCD log driver that was given at the May 7th,
2014 Certificate Transparency hack day.

You'll need go v1.1 or higher to compile.

## Website

* http://www.certificate-transparency.org/

## Building

Import into your Go workspace like this:

    go get github.com/google/ct-hackday-schwag

To compile it, run the following command from the top of your Go
workspace:

    go build src/github.com/google/ct-hackday-schwag/main/display.go

## Contributing

When sending pull requests, please ensure that everything's been run
through gofmt beforehand so we can keep everything nice and tidy.
