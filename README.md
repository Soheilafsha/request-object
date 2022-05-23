# request-object
Moralis
Moralis.Cloud.afterSave("EthTransactions", async function (request) {
  const confirmed = request.object.get("confirmed");
  if (confirmed) {
    // do something
  } else {
    // handle unconfirmed case
  }
});
