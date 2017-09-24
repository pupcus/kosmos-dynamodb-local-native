# kosmos-dynamodb-local-native

This project provides packaging for the native libraries needed for using the Amazon AWS DynamoDb local server for testing. This local server uses sqlite under the hood so the native libraries are for the connection between the aws sdk and the sqlite server.

## Usage

Nothing to do to use it. The parent project `kosmos/kosmos-dynamodb-local` has this project as a dependency and uses the contents (native libraries) to initialize the environment automatically so that the local DynamoDb server will work during testing.

## License

Kosmos is distributed under the [Eclipse Public License](http://opensource.org/licenses/eclipse-1.0.php), the same as Clojure.
