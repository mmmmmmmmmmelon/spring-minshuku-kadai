const stripe = Stripe('pk_test_51R39kNF86O6GzWRSULP0ZY5vAMwTaVOWTFzAwoqKEEus1UX5j5Rh7FtoMYZ8IWkylQtqZMRKfIOGlVAlrnAjsifb00wIhwHENu');
const paymentButton = document.querySelector('#paymentButton');

paymentButton.addEventListener('click', () => {
 stripe.redirectToCheckout({
   sessionId: sessionId
 })
});