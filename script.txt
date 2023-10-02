// JavaScript for the contact page
document.addEventListener('DOMContentLoaded', function () {
    const contactForm = document.getElementById('contact-form');
    
    contactForm.addEventListener('submit', function (e) {
        e.preventDefault();

        // You can add code here to handle form submission, e.g., sending data to a server.
        
        alert('Form submitted successfully!');
        contactForm.reset();
    });
});
