# nexus neural network architecture
Introduction
The architecture we are going to explore is a multimodal neural network designed to process and unify different modalities such as text, images, videos and sounds. This network relies on a language model based on the hyena hierarchy architecture and aims to create a unified understanding from various sources of information.

## Layer 1: Conversion to Tokens
Initially, data from various sources is provided as input. The First Layer of the architecture is the Modality Conversion Module. Its role is to transform this data into sequences of tokens, a format understandable by the network.

## Layer 2: Modal Routing
Each newly created token is then sent to the Second Layer, also known as the Modal Direction Layer. This layer determines the modality of each token (text, image, video or sound) and routes them to the appropriate processing module. If it is text, the tokens are sent directly to the central module.

## Layer 3: Specialized Processing Modules
The Third Layer houses the Specialized Processing Modules. Each module is dedicated to a specific modality (image, video, sound). The main purpose of these modules is to generate detailed textual descriptions from the incoming data. For example, for an image, the image processing module generates text tokens describing the image in detail. the tokens are then sent to the central module.

## Layer 4: Central Language Module
The Central Language Module is a key element of this architecture. Inspired by hyena hierarchy architecture, it develops like a traditional language model, but with the added ability to embed codes to identify modalities. These codes are used to mark the generated text descriptions, indicating which modality is concerned.

### Module Operation
Using the Hierarchical Hyena Architecture: The Core Module operates on the principles of the hierarchical hyena architecture, as detailed in the document "Hyena Hierarchy: Towards Larger Convolutional Language Models." This allows it to handle multimodal data and generate contextual textual descriptions.

### Generation of Multimodal Descriptions: It generates text as well as
detailed textual descriptions of the different modalities, but with the addition of codes to identify the associated modalities. These codes are inserted at specific times in the generated text.

### Encoding with Modal Codes: Generated text descriptions
are encoded with specific modal codes. Each modal code indicates which modality is described in the text of this magniere, we end up with a multitude of textual but certain tokens which allow us to describe different modalities.

### directional layer:
the directional layer identifies the different modalities thanks to the modal code and sends the different tokens to the appropriate generation module according to these ormi codes for the generated text which will be sent directly to the output module.

## Layer 5: Specialized Generative Module
The Fifth Layer of the architecture houses the Specialized Generative Modules. Each module of this layer is dedicated to a specific modality (image, video, sound). Unlike previous modules which mainly generated textual descriptions, these modules generate actual data in their respective format.

### Module Operation
Receiving Text Descriptions: Encoded text descriptions from the Central Language Module are routed to these modules. Each description contains detailed information about the corresponding modality.

### Real Data Generation: Each generation module is based
on textual descriptions to create concrete data. For example, the image generation module uses the descriptions to generate images, the video generation module creates video sequences and so on. once the tokens of the different mode generate are created, they are sent to the output module.


## layer6: output
Multimodal Fusion: The text and the different modalites generated are merged to create a global representation of the multimodal data thanks to the order previously defined by the central module
we can organize and assemble the outputs in the appropriate order

### decoding: the tokens of the different modality are then decoded for

Multimodal Fusion: Through a methodical approach, the textual content and the various generated modalities converge harmoniously, giving rise to an exhaustive representation of the multimodal data. This integration is carried out by following a predetermined schedule, meticulously established by the central module. The outputs thus generated can be systematically arranged and arranged in accordance with the appropriate arrangement, thus ensuring a coherent organization.


### neruonal architecture

This present example depicts a prospective illustration of the architectural configuration, with a visual meaning. It should be emphasized that this architecture is in an unfinished phase, and that it remains subject to further adjustments. The proposed scheme mainly aims to instill a preliminary understanding as to the potential structure of the neural network.
![Alt text](https://github.com/Nexus-labs-offcial/Nexus/blob/master/image/architechture_Nexus_modulaire.png)
