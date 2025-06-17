if (document.getElementById('product-image')) {
  const images = [
    'https://outfitters.com.pk/cdn/shop/files/F0179101901_af68bb33-09e2-4ead-9f4e-7f8baa4bca17.jpg?v=1733222503',
    'https://outfitters.com.pk/cdn/shop/files/F1028106623_1.jpg?v=1727935619',
    'https://outfitters.com.pk/cdn/shop/files/F0351109625.jpg?v=1707806134'
  ];

  let currentIndex = 0;
  const imageElement = document.getElementById('product-image');
  const leftArrow = document.querySelector('.left');
  const rightArrow = document.querySelector('.right');
  const buyNowButton = document.getElementById('buy-now');
  const notification = document.getElementById('notification');

  leftArrow.addEventListener('click', () => {
    currentIndex = (currentIndex - 1 + images.length) % images.length;
    imageElement.src = images[currentIndex];
  });

  rightArrow.addEventListener('click', () => {
    currentIndex = (currentIndex + 1) % images.length;
    imageElement.src = images[currentIndex];
  });

  buyNowButton.addEventListener('click', () => {
    notification.style.opacity = 1;
    setTimeout(() => {
      notification.style.opacity = 0;
    }, 2000);
  });
}
