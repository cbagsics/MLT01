Variables

group_id: ID of the first ticket to arrive for a given issue

num_requests: total number of requests for a given issue (parent + child tickets)

status_name: progress metrics(
             closed, in progress, open)

status_code: progress metrics(
             0 - open
             1 - closed
             2 - on hold
             3 - in progress)

dept: department assigned to handle ticket

request_type_id: ID for category that the request falls under (eg, potholes = 484)

create_date_et: date ticket was created in ET

last_action_et: last update made on the ticket

closed_date_et: date ticket was closed in ET

origin: where the ticket was reported through

neighborhood: neighborhood of the ticket

council_district: council district of the ticket

request_type_name: category name for the request (eg, potholes)

resolution_time: how many days it took to close the ticket

is_closed: boolean progress metric of ticket(
           0 - open
           1 - closed)

public_access_level: access level of the request (eg, neighborhood, block level)

closed_date_filled: date ticket was closed in ET, but with the NA filled with
                    download day (April 6); used to create request_status

request_status: status of ticket(
                less than 30 days
                more than 30 days)