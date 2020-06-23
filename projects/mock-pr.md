---
layout: project
type: project
image: images/mino/mock-pr_thumbnail.jpg
title: Mock PR
permalink: projects/mockpr
# All dates must be YYYY-MM-DD format!
date: 2020-06-23
labels:
  - C++
  - CImg
summary: A mock PR for the GBMap component of the New Haven project. 
---
```cpp
void Graph::makeGridGraph(int length, int height, NodeType nodeType)
{
	// First create all the nodes
	int totalNodes = length * height;

	for (int i = 0; i < totalNodes; i++) {
		switch (nodeType) {
		case NodeType::RESOURCE:
			this->addNode(new Resource());
			break;
		case NodeType::TILE:
			this->addNode(new TileNode());
			break;
		case NodeType::BUILDING:
			this->addNode(new BuildingTile());
			break;
		}
	}

	// Create all the edges
	for (int i = 0; i < totalNodes; i++)
	{
		// Calculations based on the node id are used to ensure connections form a grid-shaped graph. 

		if (i - length >= 0)
			nodes[0][i]->addEdge(nodes[0][i - length], Direction::UP);

		if (i + length <= totalNodes - 1)
			nodes[0][i]->addEdge(nodes[0][i + length], Direction::DOWN);

		if (i - 1 >= 0 && i % length != 0)
			nodes[0][i]->addEdge(nodes[0][i - 1], Direction::LEFT);

		if (i + 1 <= totalNodes - 1 && (i+1)%length != 0)			
			nodes[0][i]->addEdge(nodes[0][i + 1], Direction::RIGHT);
	}

	*this->length = length;
	*this->height = height;
}
```