# CachacaNER
This a Named Entity Recognition (NER) dataset in Portuguese, manually annotated, in the specific domain of the Brazilian drink called Cachaça.

The dataset containing the following seventeen categories of entities:

<table>
  <tr>
    <th>Category</th>
    <th>Tag</th>
  </tr>
  <tr>
    <td>Drink Name</td>
    <td>NOME_BEBIDA</td>
  </tr>
  <tr>
    <td>Alcoholic Graduation</td>
    <td>GRADUACAO_ALCOOLICA</td>
  </tr>
  <tr>
    <td>Drink Classification</td>
    <td>CLASSIFICACAO_BEBIDA</td>
  </tr>
  <tr>
    <td>Distillation Equipment</td>
    <td>EQUIPAMENTO_DESTILACAO</td>
  </tr>
  <tr>
    <td>Storage Time</td>
    <td>TEMPO_ARMAZENAMENTO</td>
  </tr>
  <tr>
    <td>Storage Container</td>
    <td>RECIPIENTE_ARMAZENAMENTO</td>
  </tr>
  <tr>
    <td>Wood Type</td>
    <td>TIPO_MADEIRA</td>
  </tr>
  <tr>
    <td>Sensory Characteristic - Color</td>
    <td>CARACTERISTICA_SENSORIAL_COR</td>
  </tr>
  <tr>
    <td>Sensory Characteristic - Aroma</td>
    <td>CARACTERISTICA_SENSORIAL_AROMA</td>
  </tr>
  <tr>
    <td>Sensory Characteristic - Flavor</td>
    <td>CARACTERISTICA_SENSORIAL_SABOR</td>
  </tr>
  <tr>
    <td>Sensory Characteristic - Consistency</td>
    <td>CARACTERISTICA_SENSORIAL_CONSISTENCIA</td>
  </tr>
  <tr>
    <td>Person Name</td>
    <td>NOME_PESSOA</td>
  </tr>
  <tr>
    <td>Organization Name</td>
    <td>NOME_ORGANIZACAO</td>
  </tr>
  <tr>
    <td>Location Name</td>
    <td>NOME_LOCAL</td>
  </tr>
  <tr>
    <td>Volume</td>
    <td>VOLUME</td>
  </tr>
  <tr>
    <td>Time</td>
    <td>TEMPO</td>
  </tr>
  <tr>
    <td>Price</td>
    <td>PRECO</td>
  </tr>
</table>

The CachacaNER dataset is available in IOB2 format, where a label starting with "B-" indicates that the token is the beginning of a named entity, "I-" indicates that the token is inside a named entity, and "O" indicates that the token does not pertain to any named entity. Named entities are assumed to be non-overlapping and not spanning more than one sentence.<p>
The dataset has the following attributes: token, tag, sentence number, document number, starting and ending position of the token within the sentence, partition number for cross-validation experiments (10 partitions), and whether the item is part of the training, validation or test set (70% train, 10% validation and 20% test).

<b>Cite the dataset as:</b><p>
Priscilla Silva, Arthur Franco, Thiago Santos, Mozar Brito, Denilson Pereira. CachacaNER: a Dataset for Named Entity Recognition in Texts about the Cachaça Beverage. Language Resources and Evaluation, 2023. DOI : 10.1007/s10579-023-09665-0
