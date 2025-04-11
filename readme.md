# Data Structure Visualizer

Data Structure Visualizer is an intuitive and educational web application designed to make learning data structures fun, visual, and interactive. Whether you're a beginner trying to understand the fundamentals or an advanced learner revisiting core concepts, this tool offers animated, step-by-step simulations of how various data structures work under the hood.

From inserting a node in a linked list to balancing an AVL tree or visualizing Huffman encoding in real time, this app brings abstract algorithms to life. Built with modern technologies like Next.js 15, TypeScript, and React Flow, it delivers a smooth, responsive, and visually engaging experience.

## Features

### Data Structures
- **Linked Lists**: Singly, doubly, and circular implementations
- **Stack & Queue**: LIFO/FIFO operations with visual feedback
- **Trees**: BST and AVL with auto-balancing visualizations
- **Heap**: Min/max heap implementations with heapify animations

### Applications
- **Infix to Postfix Conversion**: Expression conversion using stacks
- **Message Queue System**: Producer-consumer queue simulation
- **Polynomial Multiplication**: Using linked list representation
- **Huffman Coding**: Encoding and decoding messages using a Huffman tree
- **Dijkstra's Algorithm**: Finding the shortest path between nodes in a graph

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: TailwindCSS
- **Animations**: Framer Motion
- **Graph Visualization**: React Flow
- **UI Components**: Shadcn/ui


![Stacks](./public/ds-st.png)
![Queue](./public/ds-q.png)
![Linked List](./public/ds-ll.png)
![Polynomial](./public/ds-polynomial-multiplication.png)
![Heap](./public/ds-heap.png)
![Binary Tree](./public/ds-bst.png)
![AVL Tree](./public/ds-avl.png)
![Huffman](./public/ds-huffman.png)
![Dijkstra](./public/ds-dijkstra.png)




## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/CubeStar1/ds-visualizer.git
cd ds-visualizer
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
ds-visualizer/
├── app/                    # Next.js app router pages
├── components/            
│   ├── ui/                # shadcn/ui components
│   ├── visualizer/        # Data structure visualizations
│   ├── landing/           # Landing page components
│   └── global/            # Global components
├── hooks/                 # Custom React hooks
├── lib/                  
└── content/              # Markdown content for explanations
```



