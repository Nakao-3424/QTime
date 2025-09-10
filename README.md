# QTime
順番待ち管理システム
async function notifyCustomer(userId) {
  await fetch("https://script.google.com/macros/s/XXXXXXXX/exec", {
    method: "POST",
    body: JSON.stringify({ userId, waitMinutes: 5 }),
    headers: { "Content-Type": "application/json" },
  });
}
