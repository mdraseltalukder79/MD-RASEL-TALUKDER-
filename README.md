# MD-RASEL-TALUKDER-
package google.account;  import "google/protobuf/struct.proto";  message Account {   oneof {     string user_id = 1;     int64 gaia_id = 2;   }   string display_name = 3;   string phone_number = 4;   repeated string emails = 5;   google.protobuf.Struct properties = 6;   ... }
