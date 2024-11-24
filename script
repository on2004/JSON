const itemsContainer = document.getElementById("items-container");

// Example JSON data
const items = [
  {
    title: "Item 1",
    description: "This is the first item in the collection.",
    color: "#ff9999"
  },
  {
    title: "Item 2",
    description: "This is the second item in the collection.",
    color: "#99ff99"
  },
  {
    title: "Item 3",
    description: "This is the third item in the collection.",
    color: "#9999ff"
  }
];

// Function to render items on the page
function renderItems() {
  items.forEach(item => {
    const itemElement = document.createElement("div");
    itemElement.className = "item";
    itemElement.style.borderColor = item.color; // Use color for styling

    itemElement.innerHTML = `
      <h2>${item.title}</h2>
      <p>${item.description}</p>
    `;

    itemsContainer.appendChild(itemElement);
  });
}

// Call the function to render items
renderItems();
