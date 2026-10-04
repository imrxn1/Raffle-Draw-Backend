# Lottery API

- sell lottery ticket
- update lottery ticket
- delete lottery ticket
- get all tickets
- get ticket by id
- bulk buy(user can buy multiple at a time)
- raffle draw

# Ticket
- number(unique),
- username
- price
- timestamp

# Routes
- /tickets/t/:ticketId GET find single tickett
- /tickets/t/:ticketId PATCH update ticket by id
- /tickets/t/:ticketId DELETE delete ticket by id
- /tickets/u/:username GET find tickets for a given user
- /tickets/u/:username PATCH update tickets for a given user
- /tickets/u/:username DELETE delete all tickets for a given user
- /tickets/sell- create lottery
- /tickets/bulk - bulk sell tickets
- /tickets/draw - draw winners
- /ticket - find all lottery